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
                    <div class="lg:col-span-5">
                        <img src="./img/graphs.png" alt="graphs" class="sm:w-74 md:w-96 sm:h-74 md:h-96 mx-auto lg:mx-0">
                    </div>
                    <div class="lg:col-span-7 mt-6 lg:mt-0">
                        <div class="grid grid-cols-1 md:grid-cols-2 text-gray-900 font-semibold">
                            <div class="grid grid-cols-3">
                                <div class="col-span-2 space-y-1">
                                    <p class="">Minimum BMI:</p>
                                    <p class="">Averge BMI:</p>
                                    <p class="">Maximum BMI:</p>
                                </div>
                                <div class="col-span-1 space-y-1">
                                    <p class="text-center">19.1</p>
                                    <p class="text-center">24</p>
                                    <p class="text-center">42.5</p>
                                </div>
                            </div>
                            <div class="grid grid-cols-3 mt-3 md:mt-0">
                                <div class="col-span-2 space-y-1">
                                    <p class="">Minimum progression:</p>
                                    <p class="">Averge progression:</p>
                                    <p class="">Maximum progression:</p>
                                </div>
                                <div class="col-span-1 space-y-1">
                                    <p class="text-center">19.1</p>
                                    <p class="text-center">24</p>
                                    <p class="text-center">42.5</p>
                                </div>
                            </div>
                        </div>
                        <div class="mt-8">
                            <form action="" class="block md:flex items-center">
                                <div class="flex items-center">
                                    <label for="qa" class="text-gray-900 font-semibold">My BMI</label>
                                    <input type="text" id="qa" class="ml-4 border border-gray-900 py-1 pl-3 rounded-md" placeholder="Write here">
                                </div>
                                <a href="#" class="mt-2 md:mt-0 btn px-12 ml-8">Calculate</a>
                            </form>
                            <div class="mt-2 flex items-center">
                                <p class="text-gray-900 font-semibold">Chance of disease:</p>
                                <p class="text-red-400 font-semibold ml-4 text-lg">XX%</p>
                            </div>
                            <a href="#" class="text-blue-400 underline text-sm hover:text-blue-500">Get advice here</a>
                        </div>
                    </div>
                </div>
                <div class="w-full mt-6">
                    <div class="flex items-center justify-end space-x-5">
                        <a href="#" class="inline-block text-red-400 hover:text-red-500 font-semibold">
                            Delete dataset
                        </a>
                        <a href="#" class="btn">Edit dataset</a>
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