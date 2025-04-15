<script setup lang="ts">
import { RouterView } from 'vue-router'
import TheHeader from '@/components/TheHeader.vue'
import TheFooter from '@/components/TheFooter.vue'
</script>

<template>
  <TheHeader />
  <RouterView />
  <TheFooter />
</template>

<style>
#app {
  position: relative;
  display: flex;
  flex-direction: column;
  padding: 0 12vw;
  overflow-x: hidden;
}
</style>
