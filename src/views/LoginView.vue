<template>
    <div class="w-full h-screen flex flex-col justify-center items-center">
        <div class="text-3xl font-bold">Sing up to Ani8</div>
        <Login/>
    </div>
</template>
<script>
import Login from '../components/Login.vue';
export default{
    components:{
        Login
    }
}
</script>