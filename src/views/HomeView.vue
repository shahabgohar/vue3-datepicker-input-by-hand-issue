<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
import VueDatePicker, { type VueDatePickerProps } from '@vuepic/vue-datepicker'
import '@vuepic/vue-datepicker/dist/main.css'
import { ref } from 'vue'
const test = ref()
</script>

<template>
  <main>
    <VueDatePicker
      v-model="test"
      :autoApply="true"
      range
      text-input
    ></VueDatePicker>
  </main>
</template>
