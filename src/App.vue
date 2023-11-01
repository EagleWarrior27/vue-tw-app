<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <!-- <HelloWorld msg="Vite + Vue" />-->
  <div class="relative h-screen flex text-white">
    <div class="w-[13%] p-5 pt-6 bg-black text-gray-400 text-sm font-medium">
      <div class="flex gap-x-3">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6"><path stroke-linecap="round" stroke-linejoin="round" d="M9 9l10.5-3m0 6.553v3.75a2.25 2.25 0 01-1.632 2.163l-1.32.377a1.803 1.803 0 11-.99-3.467l2.31-.66a2.25 2.25 0 001.632-2.163zm0 0V2.25L9 5.25v10.303m0 0v3.75a2.25 2.25 0 01-1.632 2.163l-1.32.377a1.803 1.803 0 01-.99-3.467l2.31-.66A2.25 2.25 0 009 15.553z" /></svg>
        Mi Music
      </div>

      <div class="mt-10 space-y-4">
        <button class="flex gap-x-3 hover:text-white transition duration">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" /></svg>
          Inicio
        </button>
        <button class="flex gap-x-3 hover:text-white transition duration">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6"><path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" /></svg>
          Buscar
        </button>
        <button class="flex gap-x-3 hover:text-white transition duration">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6"><path stroke-linecap="round" stroke-linejoin="round" d="M12 21v-8.25M15.75 21v-8.25M8.25 21v-8.25M3 9l9-6 9 6m-1.5 12V10.332A48.36 48.36 0 0012 9.75c-2.551 0-5.056.2-7.5.582V21M3 21h18M12 6.75h.008v.008H12V6.75z" /></svg>
          Tu biblioteca
        </button>
      </div>

      <div class="mt-10 space-y-4">
        <button class="group flex gap-x-4 hover:text-white transition duration">
          <div class="w-6 h-6 grid bg-gray-400 rounded group-hover:brightness-110 transition">
            <svg class="w-4 h-4 place-self-center text-white" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M3.75 12h16.5m-16.5 3.75h16.5M3.75 19.5h16.5M5.625 4.5h12.75a1.875 1.875 0 010 3.75H5.625a1.875 1.875 0 010-3.75z" /></svg>
          </div>
          <div class="flex-1 whitespace-nowrap overflow-hidden text-ellipsis">
            Crear lista
          </div>
        </button>

        <a href="#" class="group flex gap-x-4 hover:text-white transition duration">
          <div class="w-6 h-6 grid bg-gradient-to-tl from-indigo-600 to-slate-300 rounded group-hover:brightness-110 transition">
            <svg class="w-4 h-4 place-self-center text-white" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M11.48 3.499a.562.562 0 011.04 0l2.125 5.111a.563.563 0 00.475.345l5.518.442c.499.04.701.663.321.988l-4.204 3.602a.563.563 0 00-.182.557l1.285 5.385a.562.562 0 01-.84.61l-4.725-2.885a.563.563 0 00-.586 0L6.982 20.54a.562.562 0 01-.84-.61l1.285-5.386a.562.562 0 00-.182-.557l-4.204-3.602a.563.563 0 01.321-.988l5.518-.442a.563.563 0 00.475-.345L11.48 3.5z" /></svg>
          </div>
          <div class="flex-1 whitespace-nowrap overflow-hidden text-ellipsis">
            Canciones que me gustan
          </div>
        </a>
      </div>

      <hr class="mt-5 border-gray-700">

      <div class="mt-5 font-normal hover:text-white transition duration">
        <button>
          Español
        </button>
      </div>
    </div>

    <div class="w-[87%] px-3 py-2 bg-neutral-900 text-red-500 text-2xl">Content</div>
    <div class="absolute w-full bottom-0 h-16 border-t border-neutral-700 text-red-500 text-2xl bg-neutral-900">Playback bar</div>
  </div>
</template>

<style scoped>
</style>
