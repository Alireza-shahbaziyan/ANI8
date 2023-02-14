<template>
    <div class="h-96 flex flex-col items-center">
        <HeaderBox/>
        <SearchBox />
    </div>
</template>
<script>
import HeaderBox from './BodyItems/HeaderBox.vue';
import SearchBox from './BodyItems/SearchBox.vue'
export default {
    name:"Body",
    components:{
        HeaderBox
        ,SearchBox
    }
}
</script>
