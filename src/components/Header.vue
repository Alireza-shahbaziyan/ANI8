<template>
    <header class="bg-cover bg-center bg- w-full h-screen">
    <Navbar/>
        <div class="text-white md:text-xl font-bold md:w-1/3 w-10/12 h-2/3 flex flex-col items-center justify-center">
            <div class="md:text-9xl text-6xl font-black font-sans w-full uppercase">Ani8</div>
            If you like anime or manga, Ani8 is made for you.
        </div>
    </header>
</template>
<script>
import Navbar from './Navbar.vue';

export default{
    name: "Header",
    data() {
        return {
            aniName: "demon slayer",
        };
    },
    components: { Navbar }
}
</script>
<style scoped>
header{
    background-image: url('../assets/images/image11.jpg');
}
</style>