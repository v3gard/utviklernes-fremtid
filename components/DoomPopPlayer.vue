<script setup>
import { useIsSlideActive } from '@slidev/client'
import { computed, ref } from 'vue'

const videos = [
  { id: '3TNpOD6bov8', title: 'LGTM (Looks Good to Me)', creator: 'Degenerative Pixels', start: 9 },
  { id: '6_cf9N17oVk', title: 'Human in the Loop', creator: 'Viberholten', start: 11 },
  { id: 'aLRmcVU2oWw', title: 'Obsolete (you will be)', creator: 'Hanno Lehtiniemi', start: 70 },
  { id: 'lqOAgItOueU', title: 'We Dug Our Own Grave', creator: 'Occupy SaaS', start: 8 },
]

const selected = ref(0)
const video = computed(() => videos[selected.value])
const isActive = useIsSlideActive()
</script>

<template>
  <div class="doompop">
    <iframe
      v-if="isActive"
      :key="video.id"
      class="doompop-video"
      :src="`https://www.youtube-nocookie.com/embed/${video.id}?start=${video.start}`"
      :title="`YouTube: ${video.title}`"
      allow="encrypted-media; picture-in-picture; web-share"
      referrerpolicy="strict-origin-when-cross-origin"
      allowfullscreen
    />
    <div v-else class="doompop-video" />
    <div class="doompop-choices" aria-label="Velg musikkvideo">
      <div
        v-for="(item, index) in videos"
        :key="item.id"
        class="doompop-choice"
        :class="{ selected: selected === index }"
      >
        <button type="button" :aria-pressed="selected === index" @click.stop="selected = index">
          <strong>{{ item.title }}</strong>
          <span>{{ item.creator }}<template v-if="selected === index"> · Valgt</template></span>
        </button>
        <a
          :href="`https://www.youtube.com/watch?v=${item.id}&t=${item.start}`"
          target="_blank"
          rel="noopener noreferrer"
          @click.stop
        >Se på YouTube ↗</a>
      </div>
    </div>
  </div>
</template>
