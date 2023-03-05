
<template>
    <div class="w-full lg:max-h-96 pt-10 bg-blue-100 flex flex-wrap lg: justify-around">
        <div class="w-full flex justify-between px-4">
            <div class="uppercase font-extrabold">Tranning</div>
            <div class="btn btn-ghost">View All</div>
        </div>
        <div></div>
        <div v-for="i in useStoreData.data" :key="i.id" class="m-1 text-center w-20 md:w-36 lg:w-48 hover-grow">
            <div>
                <img :src="i.image" alt="IMAGE" class="w-full rounded-md">
            </div>
            <div class="text-black text-xs md:text-lg">
                {{i.animeName}}
            </div>
        </div>
    </div>
</template>

<script setup>
import { useStore } from '@/store';
const useStoreData = useStore()
</script>