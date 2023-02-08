<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <main class="bg-cover bg-center bg-fixed box-border m-0 p-0 h-auto bg-gradient-to-r from-blue-600 to-indigo-700">
    <RouterView />
  </main>
</template>

<style scoped>
main{
  background-image: url('./assets/images/image11.jpg');
}
</style>
