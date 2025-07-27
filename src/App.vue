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

     <!-- Media Queries -->
      <div class="md:block hidden">
        <p class="text-amber-500">I appear on Larger screens</p>
      </div>
      <div class="max-md:block hidden">
        <p class="text-cyan-500">I appear on smaller screens</p>
      </div>

      <!-- Hover & buttons -->
       <button class="my-2 mx-4 rounded-lg bg-blue-500 px-4 py-2 text-white hover:bg-blue-700 focus:outline-none focus:ring focus:ring-blue-300 active:bg-blue-800">
        Click Me
       </button>

       <!-- using; first, & even -->
        <ul class="my-2 space-y-2">
          <li class="bg-white p-2 first:bg-yellow-100">Item 1</li>
          <li class="bg-white p-2 first:bg-yellow-100 odd:bg-blue-200 even:bg-green-200">Item 2</li>
          <li class="bg-white p-2 first:bg-yellow-100 odd:bg-blue-200 even:bg-green-200">Item 3</li>
          <li class="bg-white p-2 first:bg-yellow-100 odd:bg-blue-200 even:bg-green-200">Item 4</li>
          <li class="bg-white p-2 first:bg-yellow-100 odd:bg-blue-200 even:bg-green-200">Item 5</li>
        </ul>

        <!-- Theme dark with `dark` -->
         <div class="m-10 rounded-lg bg-white px-6 py-8 shadow-xl ring-1 ring-slate-900/5 dark:bg-black">
          <h3 class="text-base font-medium tracking-tight text-slate-900 dark:text-white">
            This is a text element
          </h3>
          <p class="mt-2 text-sm text-slate-500 dark:text-blue-100">
            This is an even longer p tag element.
          </p>

          <button class="text-blue-900 px-4 py-2 text-sm font-medium mt-8 bg-blue-100 rounded-md">
            Submit
          </button>
         </div>
</template>

<style scoped>

</style>
