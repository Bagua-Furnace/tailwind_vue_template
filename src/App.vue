<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>

  <div class="container mx-auto p-4">
    <h1 class="mb-4 text-9xl dark:text-amber-50">Tailwind CSS Colors and Dark Mode</h1>
    <div class="grid grid-cols-3 gap-4">
      <div class="p-4 bg-red-500 text-white">Red</div>
      <div class="p-4 bg-green-500 text-white">Green</div>
      <div class="p-4 bg-blue-500 text-white">Blue</div>
      <div class="p-4 bg-yellow-500 text-black">Yellow</div>
      <div class="p-4 bg-purple-500 text-white">Purple</div>
      <div class="p-4 bg-pink-500 text-white">Pink</div>
      <div class="p-4 bg-gray-500 text-white">Gray</div>
      <div class="p-4 bg-indigo-500 text-white">Indigo</div>
      <div class="p-4 bg-teal-500 text-white">Teal</div>
    </div>
    <div class="mt-8">
      <h2 class="text-2xl mb-4">Dark Mode Colors</h2>
      <div class="grid grid-cols-3 gap-4">
        <div class="p-4 bg-red-900 text-white">Dark Red</div>
        <div class="p-4 bg-green-900 text-white">Dark Green</div>
        <div class="p-4 bg-blue-900 text-white">Dark Blue</div>
        <div class="p-4 bg-yellow-900 text-white">Dark Yellow</div>
        <div class="p-4 bg-purple-900 text-white">Dark Purple</div>
        <div class="p-4 bg-pink-900 text-white">Dark Pink</div>
        <div class="p-4 bg-gray-900 text-white">Dark Gray</div>
        <div class="p-4 bg-indigo-900 text-white">Dark Indigo</div>
        <div class="p-4 bg-teal-900 text-white">Dark Teal</div>
      </div>
    </div>
  </div>

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
