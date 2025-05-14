<script setup>
import { ref } from 'vue'
const date = ref(
  new Date().toLocaleDateString({
    year: 'numeric',
    month: 'numeric',
    day: 'numeric',
  }),
)
</script>

<template>
  {{ date }}
</template>

<style scoped></style>
