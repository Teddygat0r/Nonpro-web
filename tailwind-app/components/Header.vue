<template>
    <header
        class="animate-fade-in my-8 flex justify-evenly text-lg font-semibold text-gray-400"
    >
        <div><h1 class="text-gray-200">Damn Feng</h1></div>
        <div class="hidden md:block"></div>
        <div class="hidden gap-16 md:flex">
            <NuxtLink class="transition duration-200 hover:text-gray-200" to="/"
                >Home</NuxtLink
            >
            <NuxtLink class="transition duration-200 hover:text-gray-200" to="/"
                >About</NuxtLink
            >
            <NuxtLink class="transition duration-200 hover:text-gray-200" to="/"
                >Balls</NuxtLink
            >
        </div>
        <div class="absolute right-0 top-0 m-4 block md:hidden">
            <Icon name="ci:hamburger-lg" color="gray" class="font-2xl" />
        </div>
    </header>
</template>

<script setup lang="ts"></script>

<style scoped>
@keyframes fade-in {
    0% {
        opacity: 0;
    }
    100% {
        opacity: 1;
    }
}

.animate-fade-in {
    animation-name: fade-in;
    animation-duration: 1s;
    animation-fill-mode: forwards;
}
</style>
