<script setup>
import { ref } from 'vue'
import '@ui5/webcomponents/dist/Title'
import '@ui5/webcomponents/dist/Label'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <ui5-title>{{ msg }}</ui5-title>
  <ui5-label> Generate your Vue application with UI5 Web Components</ui5-label>

  <p class="read-the-docs">Click on the Vite, Vue and UI5 WebComponents logos to learn more</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
