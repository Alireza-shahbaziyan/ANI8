
<template>
    <div class="w-full lg:max-h-96 pt-10 bg-blue-100 flex flex-wrap lg: justify-around">
        <div class="w-full flex justify-between px-4">
            <div class="uppercase font-extrabold">{{Title}}</div>
            <div class="btn btn-ghost">View All</div>
        </div>
        <div></div>

        <router-link  v-for="i in data.data" :key="i.id" :to="{name:'EventDetails',params:{id:i.id}}"
            class="m-1 text-center w-20 md:w-36 lg:w-48 hover-grow cursor-pointer">
            <div>
                <img :src="i.image" alt="IMAGE" class="w-full rounded-md">
            </div>
            <div class="text-black text-xs md:text-lg">
                {{ i.animeName }}
            </div>
        </router-link>
    </div>
</template>

<script>
import { useStore } from '@/store';
import { RouterLink } from 'vue-router';
import { mapState } from 'pinia'



export default {
  props: {
    Title: String
  },
  computed:{
    ...mapState(useStore, ['data'])
  }
}
</script>