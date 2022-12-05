<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <div class="container px-6">
    <p class="bg-green-700 text-gray-100">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
      magna
      aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat.
      Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur
      sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    </p>
    <p class="bg-amber-400 text-gray-700">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
      magna
      aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat.
      Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur
      sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    </p>
    <pre>
    console.log
    </pre>
    <div class="mt-[25px] bg-red-100 sm:bg-blue-200 md:bg-yellow-300 lg:bg-green-400 xl:bg-purple-500">
      <button class="bg-blue-500 text-white px-3 py-2 mx-5 my-5 rounded-md">Button</button>
      <button class="button">Button</button>
      <button class="button2">Button</button>
    </div>
  </div>
</template>
