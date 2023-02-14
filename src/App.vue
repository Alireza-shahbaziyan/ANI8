<script setup>
import { RouterLink, RouterView } from 'vue-router'
import ResponsiveNavbar from './components/ResponsiveNavbar.vue';

</script>

<template>
  <main class="box-border m-0 p-0 h-auto bg-indigo-100 text-white text-slate-600">
    <RouterView />
  </main>
</template>

<style scoped>
main{
  
}
</style>
