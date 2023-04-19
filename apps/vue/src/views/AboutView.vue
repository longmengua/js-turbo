<script setup lang="ts">
import UiLibDemo from '../components/UiLibDemo.vue'
</script>

<template>
  <main>
    <UiLibDemo msg="demo" />
  </main>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
