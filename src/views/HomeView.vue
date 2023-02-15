<script>
import Header from '../components/Header.vue';
import Body from '../components/Body.vue';
import Footer from '../components/Footer.vue';
export default {
  components: {
    Header,
    Body,Footer
}
}
</script>

<template>
  <div class="flex flex-col w-full">
    <Header/>
    <Body/>
    <Footer/>
  </div>
</template>
