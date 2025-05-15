<script setup>
import { ref } from 'vue'
const date = ref(
  new Date().toLocaleDateString('ru-RU', {
    year: 'numeric',
    month: 'numeric',
    day: 'numeric',
  }),
)
</script>

<template>
  <div>{{ date }}</div>
</template>

<style scoped></style>
