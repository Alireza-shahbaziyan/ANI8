<template>
    <div class="w-full lg:h-72 pt-10 bg-blue-100">
        <div class="w-full flex justify-between px-4">
            <div class="uppercase font-extrabold">Tranning</div>
            <div class="btn btn-ghost">View All</div>
        </div>
        <div class="flex justify-around flex-wrap py-4">
            <div v-for="item in useStoreData.data" :key="item.id" class="p-1 m-1 flex justify-center items-center flex-col">
                <img :src="item.image" alt="IMAGE" class="h-28 lg:h-44 w-4/5 lg:w-full">
                <div class="capitalize font-semibold textarea-xs text-slate-500 mt-2">{{item.animeName }}</div>
            </div>
        </div>
    </div>
</template>
<script setup>
import { useStore } from '@/store';

const useStoreData = useStore()

</script>