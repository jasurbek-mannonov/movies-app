<script setup>
</script>

<template>
    <div class="flex flex-col md:flex-row">
        <div class="md:w-1/2 p-8">
            <img src="https://cdn.pixabay.com/photo/2015/11/03/08/58/meeting-1019875_960_720.jpg" alt="Contact Us"/>
        </div>
        <div class="md:w-1/2 p-8 shadow-md">
            <p class="text-lg mb-2">
                7 Buyuk Kelajak street <br />
                Gulistan, Sirdaryo 301100
            </p>
            <p class="text-lg mb-2">
                Phone: +998 90 241 68 57 <br />
                Email: jasurbekmannonov2020@gmail.com
            </p>
            <form>
                <label for="name" class="block text-lg font-bold mb-2">Name</label>
                <input type="text" id="name" class="w-full border border-gray-300 p-2 mb-4 rounded-lg"/>
                <label for="email" class="block text-lg font-bold mb-2">Email</label>
                <input type="text" id="email" class="w-full border border-gray-300 p-2 mb-4 rounded-lg"/>

                <label for="name" class="block text-lg font-bold mb-2">Message</label>
                <textarea name="message" id="message" class="w-full border border-gray-300 p-2 mb-4 rounded-lg"></textarea>
                <button type="submit" class="bg-rose-500 hover:bg-rose-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline">Submit</button>
            </form>
        </div>
    </div>
</template>