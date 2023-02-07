<template>
    <div class="w-full absolute flex justify-center bg-gradient-to-r from-blue-600 to-indigo-700">
        <HeaderBox PartName="Wallpapers"/>``
    </div>
</template>

<script>
import HeaderBox from './HeaderBox.vue';
export default {
    data() {
        return {
            Name: "wallpapers",
        }
    },
    components:{
        HeaderBox
    }
}
</script>