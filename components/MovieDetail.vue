<script setup>

</script>
<template>
    <div class="grid sm:grid-cols-3 gap-7 justify-items-center m-10">
        <!-- Column 1: Image -->
        <div class="bg-white rounded-lg shadow-md overflow-hidden">
            <img class="h-400 w-full object-cover" src="https://www.themoviedb.org/t/p/w600_and_h900_bestv2/74xTEgt7R36Fpooo50r9T25onhq.jpg" alt=""/>
        </div>

        <!-- Column 2: Title, Overview, Revenue, Buy Button -->
        <div class="sm:col-span-2 mx-6">
            <h1 class="font-bold text-2xl mb-5">Batman</h1>
            <h3 class="font-semibold text-lg mb-5">Release Date: 22-01-2024</h3>
            <p class="text-gray-500 text-md mb-8">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem similique dolorum nam, at facere pariatur tenetur excepturi autem animi minima delectus commodi ipsa tempore maxime, aut, quisquam magnam esse? Ducimus.
            </p>

            <p class="text-gray-500 text-md">Revenue: $ 231 562</p>

            <div class="mt-6">
                <button class="bg-indigo-500 hover:bg-indigo-600 text-white font-medium py-2 px-4 rounded">
                    Watch Trailer
                </button>
                <button class="bg-rose-500 hover:bg-rose-600 text-white font-medium py-2 px-4 rounded m-5">
                    Buy Now
                </button>
            </div>
        </div>
    </div>
</template>