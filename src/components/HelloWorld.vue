<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <p> Generate your Vue application with UI5 Web Components</p>

  <p class="read-the-docs">Click on the Vite, Vue and UI5 WebComponents logogs to learn more</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
