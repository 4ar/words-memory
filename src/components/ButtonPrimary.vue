<script setup></script>
<template>
  <button class="btn-primary">
    <slot />
  </button>
</template>
<style scoped>
.btn-primary {
  display: block;
  background-color: var(--primaryColor);
  color: var(--white);
  border-radius: 100px;
  border: 0;
  font-weight: 400;
  font-size: 24px;
  padding: 16px 10px;
  width: 335px;
  height: 68px;
  cursor: pointer;
}

.btn-primary:hover {
  background-color: var(--primaryColorHover);
}
</style>
