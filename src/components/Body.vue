<template>
    <div class="h-96 flex flex-col items-center">
        <HeaderBox/>
        <SearchBox />
        <div class="text-3xl">{{ data }}</div>
    </div>
</template>
<script>
import {mapState} from 'vuex'
import HeaderBox from './BodyItems/HeaderBox.vue';
import SearchBox from './BodyItems/SearchBox.vue'
export default {
    name:"Body",
    components:{
        HeaderBox
        ,SearchBox
    },
    computed:mapState({
        data:store => store.data
    })
}
</script>
