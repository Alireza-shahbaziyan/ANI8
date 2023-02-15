<template>
    <div class=" w-4/5 h-96 md:w-3/5 lg:w-2/5 mt-10 ">
        <form class="form-control flex flex-col justify-center items-center">
            <input type="email" class="input w-full my-2 bg-white" placeholder="Email">
            <input type="text" class="input w-full my-2 bg-white" placeholder="UserName">
            <input type="password" class="input w-full my-2 bg-white" placeholder="Password">
            <input type="password" class="input w-full my-2 bg-white" placeholder="confirm Password">
            <!-- <input type="submit" value="Login" class="btn btn-wide w-full my-2"> -->
                <div class="flex flex-col justify-center items-center">
                    <label class="label cursor-pointer">
                        <input type="checkbox"  class="checkbox" />
                        <span class="label-text m-1 font-semibold">You agree to our terms of service</span>
                </label>
                </div>
                <input type="submit" value="Sing Up" class="btn btn-info text-white">
        </form>
        

    </div>
</template>