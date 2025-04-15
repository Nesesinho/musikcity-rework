<script setup lang="ts">
import FirstSec from "/src/components/home/FirstSec.vue";
import SecondSec from "/src/components/home/SecondSec.vue";
import ThirdSec from "/src/components/home/ThirdSec.vue";
</script>

<template>
  <main>
    <img src="/public/imgs/bg-party.png" class="bg" alt="">
    <FirstSec />
    <ThirdSec />
    <SecondSec />
  </main>
</template>

<style scoped>
  main {
    display: flex;
    flex-direction: column;
    align-items: end;
    padding: 8vh 0;
    flex: 1;
  }

  .bg {
    position: absolute;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    z-index: -10;

  }
</style>
