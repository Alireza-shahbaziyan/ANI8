<template>
    <header class="bg-cover bg-center bg- w-full h-screen">
    <Navbar/>
        <div class="text-white text-xl font-bold w-1/3 h-2/3 flex flex-col items-center justify-center">
            <div class="text-9xl font-black font-sans w-full uppercase">Ani8</div>
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