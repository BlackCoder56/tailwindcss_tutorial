<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
    <h1 class="text-center text-lg text-green-400">Hello World</h1>

    <div class="w-full h-10 bg-violet-200 border-violet-600 border-2 rounded-md my-4 p-2">
      <p class="text-center font-mono font-extrabold">A div</p>
    </div>

    <!-- Layout -->
     <div class="fixed w-10 h-10 bg-red-500 top-0"></div>

     <div class="flex justify-between">
      <div class="h-16 w-16 rounded-full bg-blue-500"></div>
      <div class="h-16 w-16 rounded-full bg-blue-500"></div>
      <div class="h-16 w-16 rounded-full bg-blue-500"></div>
     </div>

     <div class="grid grid-cols-3 gap-2">
      <div class="bg-violet-500 h-12"></div>
      <div class="bg-violet-500 h-12"></div>
      <div class="bg-violet-500 h-12"></div>
      <div class="bg-violet-500 h-12"></div>
      <div class="bg-violet-500 h-12"></div>
      <div class="bg-violet-500 h-12"></div>
     </div>
</template>

<style scoped>

</style>
