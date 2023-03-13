<template>
    <div class="flex flex-col items-center bg-blue-100">
        <HeaderBox/>
        <SearchBox/>
        <BodyRow Title="Traning"/>
        <BodyRow Title="News"/>
        <BodyRow Title="Popular"/>
    </div>
</template>
<script>
import BodyRow from './BodyItems/BodyRow.vue';
import HeaderBox from './BodyItems/HeaderBox.vue';
import SearchBox from './BodyItems/SearchBox.vue'
export default {
    name: "Body",
    components: {
        HeaderBox,
        SearchBox,
        BodyRow
    },
}
</script>
