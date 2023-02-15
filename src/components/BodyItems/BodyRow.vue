<template>
    <div class="w-full lg:h-60 pt-10 bg-blue-100">
        <div class="w-full flex justify-between px-4">
            <div class="uppercase font-bold">{{ RowName }}</div>
            <div class="">View All</div>
        </div>
        <div class="flex justify-around flex-wrap">
            <div v-for="item in data" :key="item.id" class="p-1 m-1 flex justify-center items-center flex-col">
                <img :src="item.image" alt="IMAGE" class="h-28 lg:h-36 w-4/5 lg:w-full">
                {{item.title }}
            </div>
        </div>
    </div>
</template>
<script>
import { mapState } from 'vuex'

export default {
    name: 'BodyRow',
    data() {
        return {
            RowName:'Trending Now'
        }
    },
    computed: mapState({
        data: store => store.data
    })
}
</script>