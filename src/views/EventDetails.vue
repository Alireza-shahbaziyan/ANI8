<template>
    <div class="text-3xl text-black font-bold w-full text-center mt-80">
        {{ id }}
    </div>
</template>
<script >
import { useStore } from '@/store';
import { mapState } from 'pinia'

export default {
    name: 'EventDetails',
    props: ['id'],
   computed: {
    ...mapState(useStore,['data']),
   }
}
</script>