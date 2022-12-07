<script setup>
import { ref } from 'vue'

defineProps({
  title: String
})

</script>

<template>
  <h1 class="text-4xl text-center font-bold mb-10">{{ title }}</h1>

  <div class="logo-row">
    <!--    Vue Logo-->
    <a href="https://vuejs.org/" class="group" target="_blank">
      <img src="/src/assets/vue.svg" alt="Vue logo" />
      <span class="group-hover:opacity-100">Vite</span>
    </a>
    <!--    Vite Logo-->
    <a href="https://vitejs.dev" class="group" target="_blank">
      <img src="/src/assets/vite.svg" alt="Vite logo" />
      <span class="group-hover:opacity-100">Vite</span>
    </a>


    <!--    sass logo-->
    <a href="https://tailwindcss.com//" class="group" target="_blank">
      <img src="/src/assets/tailwind.svg" alt="Tailwind Logo" />
      <span class="group-hover:opacity-100">Tailwind CSS</span>
    </a>
    <!--    sass logo-->
    <a href="https://sass-lang.com/" class="group" target="_blank">
      <img src="/src/assets/sass.svg" alt="SASS Logo" />
      <span class="group-hover:opacity-100">SASS Preprocessor</span>
    </a>
    <!--    andy logo-->
    <a href="https://andyterry.co.uk" class="group" target="_blank">
      <img class="rounded-full" src="/src/assets/andy.svg" alt="Andy logo" />
      <span class="group-hover:opacity-100 mx-auto">Andy Terry</span>
    </a>

  </div>
</template>


