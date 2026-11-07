<script setup>
import { computed } from 'vue'

const props = defineProps({
  stage: { type: Number, required: true },
})

const skills = [
  { name: 'IT og utforsking', since: 1, updates: [1] },
  { name: 'Support', since: 2, updates: [2] },
  { name: 'Programmering og web', since: 3, updates: [3, 4] },
  { name: 'Samhandling og formidling', since: 5, updates: [5] },
  { name: 'Nettverk og drift', since: 6, updates: [6] },
  { name: 'IT-sikkerhet', since: 7, updates: [7] },
  { name: 'Domene, testing, leveranseevne', since: 8, updates: [8] },
  { name: 'Teknisk ledelse', since: 9, updates: [9] },
  { name: 'Sky og utvikling', since: 10, updates: [10] },
]

const messages = [
  'IT og utforsking låst opp',
  'Support låst opp',
  'Programmering og web låst opp',
  'Programmering styrket: Delphi',
  'Samhandling og formidling låst opp',
  'Nettverk og drift styrket',
  'IT-sikkerhet låst opp',
  'Domene, testing, leveranseevne låst opp',
  'Teknisk ledelse styrket',
  'Sky og utvikling styrket',
]

const message = computed(() => messages[props.stage - 1])
</script>

<template>
  <aside class="skill-panel" aria-label="Ferdigheter som utvikles gjennom livshistorien">
    <div class="skill-panel-heading">
      <span>FERDIGHETER</span>
      <span>UNDER UTVIKLING ↑</span>
    </div>
    <div class="skill-list">
      <div
        v-for="skill in skills"
        :key="skill.name"
        class="skill-row"
        :class="{
          'skill-active': stage >= skill.since,
          'skill-new': skill.updates.includes(stage),
        }"
      >
        <span>{{ skill.name }}</span>
        <span class="skill-status">{{ stage >= skill.since ? '✓' : '–' }}</span>
      </div>
    </div>
    <div class="skill-toast" aria-live="polite">
      <span class="toast-label">NYTT STEG</span>
      <span>{{ message }}</span>
    </div>
  </aside>
</template>
