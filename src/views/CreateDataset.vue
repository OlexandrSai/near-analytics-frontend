<template>
  <header class="bg-gray-900 text-white relative">
        <nav class="">
            <div class="container mx-auto px-6">
                <div class="hidden md:flex items-center py-3">
                    <div class="">
                        <a href="" class="text-lg">NEAR-Analytics</a>
                        <p class="text-sm text-gray-200 hidden lg:block">The first step to bringing AI to the NEAR blockhain</p>
                    </div>
                    <ul class="flex space-x-10 ml-auto">
                        <li><a href="#" class="hover:underline">Home</a></li>
                        <li><a href="#" class="hover:underline">Datasets</a></li>
                        <li><a href="#" class="hover:underline">Menu</a></li>
                        <li><a href="#">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                            </svg>
                        </a></li>
                    </ul>
                    <a href="#" class="inline-block text-blue-400 border border-blue-400 rounded-md px-6 py-2 hover:bg-gray-800 ml-12 hover:shadow-md">Login with NEAR</a>
                </div>
                <div class="flex justify-between items-center py-3 px-4 md:hidden">
                    <a href="#" class="">NEAR-Analytics</a>
                    <a href="#" class="">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
                        </svg>
                    </a>
                </div>
            </div>
        </nav>
        <div class="absolute top-0 w-full h-64 bg-gray-900" style="z-index: -10;">

        </div>
    </header>
    <section class="mt-4 md:mt-16">
        <div class="container mx-auto px-6">
            <div class="w-full bg-white rounded-lg shadow-lg px-6 md:px-32 py-16 gradient-offer">
                <a href="#" class="text-blue-400 hover:underline flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16l-4-4m0 0l4-4m-4 4h18" />
                      </svg>
                    cancele creating
                </a>
                <div class="block md:flex items-top mt-6">
                    <div class="w-full lg:w-1/2 space-y-4">
                        <h3 class="text-2xl font-medium text-gray-900">Create dataset</h3>
                        <form action="" class="">
                            <div class="block space-y-2">
                                <h2 class="text-gray-900 font-medium text-xl">Name</h2>
                                <input type="text" id="name" class="w-full py-2 pl-6 border border-gray-900 rounded-md gradient-interact" placeholder="Write here">
                            </div>
                            <div class="mt-6 block space-y-2">
                                <h2 class="text-gray-900 font-medium text-xl">Description</h2>
                                <textarea type="text" id="name" class="w-full h-52 py-2 pl-6 border border-gray-900 rounded-md gradient-interact"></textarea>
                            </div>
                            <div class="flex justify-end mt-2">
                                <a href="#" class="inline text-blue-400 hover:underline">+ add dataset cover</a>
                            </div>
                            <div class="flex justify-center mt-4">
                                <a href="#" class="btn w-1/2 mx-auto">Create</a>
                            </div>
                        </form>
                    </div>
                    <div class="hidden lg:block w-full mt-6 md:mt-0 md:w-1/2">
                        <img src="./img/image 1.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>

</style>