<template>
    <div class=" bg-slate-800 flex flex-col md:flex-row justify-center items-center md:mx-6">
        <!-- body Items -->
        <div class="wallpaper mt-12 md:w-3/6 w-4/5 md:h-96 h-64 bg-cover rounded-3xl text-center">
            <div class="w-full h-full backdrop-blur-sm text-5xl myfont flex justify-center items-center">Wallpapers </div>
        </div>
        <div class="md:w-3/6 w-full flex justify-center items-center flex-col">
            <div class="news my-6 w-4/5 h-64 bg-cover rounded-3xl text-center">
                <div class="w-full h-full backdrop-blur-sm text-5xl myfont  flex justify-center items-center">Top news </div>
            </div>
            <div class="animes mb-6 w-4/5 h-64 bg-cover rounded-3xl text-center bg-white">
                <div class="w-full h-full backdrop-blur-sm text-5xl myfont  flex justify-center items-center">Animes</div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:"Body",
}
</script>
<style scoped>
.wallpaper{
    background-image: url('../assets/images/image1.jpg');
}
.news{
    background-image: url('../assets/images/image5.jpg');
}
.animes{
    background-image: url('../assets/images/image9.jpg');
}
</style>
