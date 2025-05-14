<template>
  {{ date }}
</template>


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

<style scoped></style>
