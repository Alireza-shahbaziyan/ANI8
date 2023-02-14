<template>
    <ResponsiveNavbar />
    <header class=" w-full h-96 overflow-hidden bg-gradient-to-r from-indigo-600 to-fuchsia-700 text-center">
        <div
            class="text-white md:text-xl
             font-serif bg-none 
               md:w-1/3s w-full h-full 
                flex flex-col items-center md:justify-center justify-center mx-4">
            <div class="md:text-9xl text-7xl font-black myfont w-full uppercase">
              Welcome to <span class="text-fuchsia-500">A</span><span class="text-orange-500">N</span><span class="text-sky-500">I</span><span class="text-red-500">8</span>
            </div>
            <div class="font-serif font-thin">Track ,share and discover your favorite anime and manga with Ani8</div>
        </div>
    </header>
</template>

<script>
import ResponsiveNavbar from './ResponsiveNavbar.vue';

export default {
    name: "Header",
    data() {
        return {
            aniName: "demon slayer",
        };
    },
    components: { ResponsiveNavbar }
}
</script>
<style scoped>
header {
    /* border-radius: 0 0 85% 85% / 30%; */
    /* background-image: url('../assets/images/image11.jpg'); */
}
</style>