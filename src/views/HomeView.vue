<script setup lang="ts">
import FirstSec from "@/components/home/FirstSec.vue";
import SecondSec from "@/components/home/SecondSec.vue";
import ThirdSec from "@/components/home/ThirdSec.vue";
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

  @media (max-width: 768px) {
    .bg {
      width: auto;
      height: 100vh;
    }
  }
</style>
