<script setup lang="ts">
import { RouterView } from 'vue-router'
import TheHeader from '/src/components/TheHeader.vue'
</script>

<template>
  <TheHeader />
  <RouterView />
</template>

<style>
#app {
  position: relative;
  display: flex;
  flex-direction: column;
  padding: 0 8rem;
  overflow-x: hidden;
}
</style>
