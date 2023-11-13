<script setup>
definePageMeta({
    layout: "custom",
});
</script>

<template>
    <div class="w-full max-w-md mx-auto mt-5">
        <form class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4">
            <div class="mb-4">
                <label class="block text-gray-700 font-bold mb-2" for="username">
                    Username
                </label>
                <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" type="text" id="username" placeholder="Username"/>
            </div>

            <div class="mb-4">
                <label class="block text-gray-700 font-bold mb-2" for="email">
                    Email
                </label>
                <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" type="email" id="email" placeholder="Email"/>
            </div>

            <div class="mb-4">
                <label block text-gray-700 font-bold mb-2 for="password">
                    Password
                </label>
                <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" type="password" id="password" placeholder="Password"/>
            </div>
            <div class="mb-4">
                <label block text-gray-700 font-bold mb-2 for="rePassword">
                  Repeat password
                </label>
                <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" type="password" id="rePassword" placeholder="Repeat password"/>
            </div>
            <div class="flex items-center justify-center mt-6">
                <button class="bg-rose-500 hover:bg-rose-700 text-white font-bold py-2 px-8 rounded-full focus:outline-none focus:shadow-outline" type="button">
                    Sign Up
                </button>
            </div>
        </form>
    </div>
</template>