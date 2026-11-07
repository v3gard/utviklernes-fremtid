<script setup>
import { onMounted, onUnmounted, ref } from 'vue'

const reducedMotion = ref(true)
const videoFailed = ref(false)
let motionPreference

function updateMotionPreference(event) {
  reducedMotion.value = event.matches
}

onMounted(() => {
  motionPreference = window.matchMedia('(prefers-reduced-motion: reduce)')
  updateMotionPreference(motionPreference)
  motionPreference.addEventListener('change', updateMotionPreference)
})

onUnmounted(() => {
  motionPreference?.removeEventListener('change', updateMotionPreference)
})
</script>

<template>
  <img
    v-if="reducedMotion || videoFailed"
    class="title-image"
    src="/images/title.webp"
    alt=""
  />
  <video
    v-else
    class="title-image"
    src="/images/title.mp4"
    poster="/images/title.webp"
    autoplay
    muted
    loop
    playsinline
    aria-hidden="true"
    @error="videoFailed = true"
  />
</template>
