<template>
  <nav class="
          flex flex-wrap
          items-center
          justify-between
          w-full
          py-2
          md:py-0
          px-2
          text-lg 
          bg-gradient-to-r from-blue-600 to-indigo-700
        ">
    <div class=" text-white uppercase text-3xl btn btn-ghost myfont">
      ani8
    </div>
    <div @click="menuStatus = !menuStatus" class="btn btn-ghost">
      <svg xmlns="http://www.w3.org/2000/svg" id="menu-button" class="h-6 w-6 cursor-pointer md:hidden block"
        fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
      </svg>
    </div>
    <div class="w-full md:flex md:items-center md:w-auto" :class="menuStatus ? '' : 'hidden'">
      <ul class="
              pt-4
              text-base text-gray-200
              md:flex
              md:justify-between 
              md:pt-0">
        <li>
          <div class="btn btn-ghost"><a class="md:p-4 py-2 block hover:text-purple-400" href="#">Manga</a></div>
        </li>
        <li>
          <div class="btn btn-ghost "><a class="md:p-4 py-2 block hover:text-purple-400" href="#">About me</a></div>
        </li>
        <li>
          <div class="btn btn-ghost "><a class="md:p-4 py-2 block hover:text-purple-400 " href="#">Sign Up</a></div>
        </li>
        <li>
          <a class="md:p-4 py-2 block hover:text-purple-400" href="#">
            <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor"
              class="bi bi-github inline" viewBox="0 0 16 16">
              <path
                d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z" />
            </svg></a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      menuStatus: false,
      menuItem: ''
    }
  },
  // computed:{
  //     menuStatus(){
  //         return this.menuStatus = !this.menuStatus
  //     },
  // }
}
</script>