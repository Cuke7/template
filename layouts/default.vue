<template>
  <div class="flex h-screen flex-col" id="parent1" data-theme="dark">
    <div></div>
    <div class="flex w-full justify-between bg-white bg-opacity-20 px-20 py-6">
      <NuxtLink to="./"><HomeIcon class="h-8 w-8 text-white" /></NuxtLink>
      <div>
        <NuxtLink to="./pictures" class="text-lg text-white underline"
          >Pictures</NuxtLink
        >
      </div>
    </div>
    <slot></slot>
  </div>
</template>

<script lang="ts" setup>
import { HomeIcon } from "@heroicons/vue/24/outline";
</script>

<style scoped>
#parent1 {
  background-image: linear-gradient(
    to right bottom,
    #0d4613,
    #004233,
    #003b4c,
    #003056,
    #13224c
  );
}
</style>
