<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>

  <nav class="p-5 text-white bg-slate-800 sticky top-0 z-50 md:flex md:items-center md:justify-between">
    <span class="text-2xl font-[Poppins] font-bold">
      Cristian Fotofraga
    </span>
    <ul class="md:flex md:items-center">
      <li class="mx-4">
        <a href="#" class="text-xl hover:text-cyan-500 duration-500">Início</a>
      </li>
      <li class="mx-4">
        <a href="#" class="text-xl hover:text-cyan-500 duration-500">Portfólio</a>
      </li>
      <li class="mx-4">
        <a href="#" class="text-xl hover:text-cyan-500 duration-500">Contato</a>
      </li>
    </ul>
</nav>
<header class="h-screen object-cover snap-proximity snap-y snap-start">
  <img src="https://images.unsplash.com/photo-1542038784456-1ea8e935640e?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80" class="object-cover w-full h-full"/>    
</header>
    <div class="h-screen bg-white snap-proximity snap-y">
      <div class="snap-start">
      </div>
    </div>
</template>

<style scoped>
</style>
