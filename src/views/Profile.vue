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
                    <a href="#" class="inline-block text-blue-400 border border-blue-400 rounded-md px-6 py-2 hover:bg-gray-800 ml-12 hover:shadow-md">
                        Nazar Nyzhnyk
                    </a>
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
            <div class="relative w-full bg-white rounded-lg shadow-lg px-4 md:px-6 lg:px-12 py-6 md:py-16 gradient-offer" style="z-index: 1;">

                <div class=" block md:grid grid-cols-1 lg:grid-cols-12 gap-x-8" >
                    <div class="md:col-span-6 lg:col-span-4 xl:col-span-3">
                        <div class="h-64 w-64 bg-gray-900 rounded-md flex items-center justify-center mx-auto md:mx-0">
                            <p class="text-white">No image here</p>
                        </div>
                        <h2 class="text-gray-900 text-xl font-semibold mt-2 text-center md:text-left">Nazar Nyzhnyk</h2>
                        <h3 class="text-gray-700 font-semibold text-center md:text-left">nazarh2onyzhnyk.near</h3>
                    </div>
                    <div class="md:col-span-6 mt-6 md:mt-0 lg:col-span-4 xl:col-span-3 space-y-6">
                        <a href="#" class="btn w-full">
                            Create new dataset
                        </a>
                        <a href="#" class="btn w-full">
                            Edit profile
                        </a>
                        <a href="#" class="block py-2 w-full rounded-md text-red-400 font-semibold 
                                            border border-red-400 hover:bg-red-100 text-center 
                                            active:bg-red-300 active:text-white transition duration-400">
                            Logout
                        </a>
                    </div>
                    <div class="md:col-span-12 mt-6 lg:mt-0 lg:col-span-4 xl:col-span-6">
                        <p class="text-gray-900">
                            Ipsum id arcu lobortis in in adipiscing laoreet. In pretium, posuere non, 
                            vitae gravida id magnis molestie elementum. Id aliquam ac aenean diam et 
                            consequat pharetra viverra sagittis. Et enim pharetra, ipsum donec suspendisse 
                            amet, in. Id amet congue pellentesque sit. Sit volutpat, feugiat ridiculus sed 
                            at convallis scelerisque. Nisl ipsum, tempor sed sed viverra. Tortor mauris 
                            lectus mus dui, ut. Viverra fusce faucibus mattis etiam pretium leo congue 
                            aenean sit. Iaculis nunc leo aenean mauris lacus in ipsum.
                        </p>
                    </div>
                </div>
                 <!-- Deco -->
                 <div class="">
                    <img src="./img/rec-sm.png" alt="rec-sm" class="absolute top-0 left-0" style="z-index: -1;">
                    <img src="./img/rec-big.png" alt="rec-big" class="absolute bottom-0 right-0" style="z-index: -1;">
                    <img src="./img/violet.png" alt="violet" class="hidden md:block absolute h-96 w-96 bottom-0 right-32" style="z-index: -1;">
                </div>
                <!-- Deco -->
            </div>
        </div>
    </section>
    <section class="mt-8">
        <div class="container mx-auto px-6">
            <h3 class="text-2xl font-medium text-gray-900">My datasets</h3>
            <div class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-6 my-6 gap-x-4 xl:gap-x-12 gap-y-6 lg:gap-y-0 relative">
                <div class="gradient-offer rounded-md shadow-md hover:shadow-2xl">
                    <a href="#" class="block">
                        <img src="./img/diabetes.png" alt="diabetes" class="w-full rounded-md">
                        <div class="px-4 pt-2">
                            <h4 class="text-xl text-gray-900">Diabetes</h4>
                            <p class="text-gray-700 leading-5">2 dataset in there</p>
                            <p class="text-gray-700 leading-5">13 views</p>
                        </div>
                        <a href="#" class="block text-blue-400 hover:underline text-center my-4">View</a>
                    </a>
                </div>
                <div class="gradient-offer rounded-md shadow-md hover:shadow-2xl">
                    <a href="#" class="block">
                        <img src="./img/diabetes.png" alt="diabetes" class="w-full rounded-md">
                        <div class="px-4 pt-2">
                            <h4 class="text-xl text-gray-900">Diabetes</h4>
                            <p class="text-gray-700 leading-5">2 dataset in there</p>
                            <p class="text-gray-700 leading-5">13 views</p>
                        </div>
                        <a href="#" class="block text-blue-400 hover:underline text-center my-4">View</a>
                    </a>
                </div>
                <div class="gradient-offer rounded-md shadow-md hover:shadow-2xl">
                    <a href="#" class="block">
                        <img src="./img/diabetes.png" alt="diabetes" class="w-full rounded-md">
                        <div class="px-4 pt-2">
                            <h4 class="text-xl text-gray-900">Diabetes</h4>
                            <p class="text-gray-700 leading-5">2 dataset in there</p>
                            <p class="text-gray-700 leading-5">13 views</p>
                        </div>
                        <a href="#" class="block text-blue-400 hover:underline text-center my-4">View</a>
                    </a>
                </div>
                <div class="gradient-offer rounded-md shadow-md hover:shadow-2xl">
                    <a href="#" class="block">
                        <img src="./img/diabetes.png" alt="diabetes" class="w-full rounded-md">
                        <div class="px-4 pt-2">
                            <h4 class="text-xl text-gray-900">Diabetes</h4>
                            <p class="text-gray-700 leading-5">2 dataset in there</p>
                            <p class="text-gray-700 leading-5">13 views</p>
                        </div>
                        <a href="#" class="block text-blue-400 hover:underline text-center my-4">View</a>
                    </a>
                </div>
                <div class="gradient-offer rounded-md shadow-md hover:shadow-2xl">
                    <a href="#" class="block">
                        <img src="./img/diabetes.png" alt="diabetes" class="w-full rounded-md">
                        <div class="px-4 pt-2">
                            <h4 class="text-xl text-gray-900">Diabetes</h4>
                            <p class="text-gray-700 leading-5">2 dataset in there</p>
                            <p class="text-gray-700 leading-5">13 views</p>
                        </div>
                        <a href="#" class="block text-blue-400 hover:underline text-center my-4">View</a>
                    </a>
                </div>
                <div class="gradient-offer rounded-md shadow-md hover:shadow-2xl">
                    <a href="#" class="block">
                        <img src="./img/diabetes.png" alt="diabetes" class="w-full rounded-md">
                        <div class="px-4 pt-2">
                            <h4 class="text-xl text-gray-900">Diabetes</h4>
                            <p class="text-gray-700 leading-5">2 dataset in there</p>
                            <p class="text-gray-700 leading-5">13 views</p>
                        </div>
                        <a href="#" class="block text-blue-400 hover:underline text-center my-4">View</a>
                    </a>
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