<template>
    <header
        class="flex my-8 text-lg font-semibold text-gray-400 justify-evenly"
    >
        <div><h1 class="text-gray-200">Logo</h1></div>
        <div></div>
        <div class="flex gap-16">
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
    </header>
</template>

<script setup lang="ts"></script>

<style scoped></style>
