<script setup lang="ts">
import { ref } from 'vue';

let count = ref(0);
</script>

<template>
  <div class="flex flex-col justify-center items-center h-screen text-gray-900">
    <h1 class="font-bold text-6xl">Count {{count}}</h1>
    <button class="border border-gray-900 p-3 rounded-full w-52 mt-5" @click="count++">Increment</button>
    <button class="border border-gray-900 p-3 rounded-full w-52 mt-5" @click="count--">Decrement</button>
  </div>
</template>

<style lang="scss">
@tailwind base;
@tailwind components;
@tailwind utilities;
@tailwind variants;
</style>
