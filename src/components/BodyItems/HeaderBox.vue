<template>
    <router-link to="/login">
        <div class="bg-blue-600 border-0 text-white btn rounded-3xl btn-lg -m-8">
            Join Now
            <kbd class="kbd bg-transparent border-0">▶︎</kbd>
        </div>
    </router-link>
</template>

<script>
import { RouterLink } from 'vue-router';
export default {
    name: "HeaderBox",
    // props: {
    //     PartName: String,
    // }
}
</script>
