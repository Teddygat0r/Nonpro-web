<template>
    <footer class="flex h-full w-full justify-evenly gap-4 bg-gray-950 py-[3%]">
        <div class="hidden md:block"></div>
        <div class="flex flex-col text-center md:text-left">
            <div><h4 class="text-lg font-bold">Damn Feng</h4></div>
            <div class="h-8"></div>
            <div>
                <p class="text-gray-400">
                    © 2023 Joshua Zhang. All Rights Reserved
                </p>
            </div>
            <div>
                <p class="text-gray-400">
                    Check out my other work:
                    <NuxtLink
                        to="https://teddygat0r.vercel.app"
                        class="text-cyan-500 underline hover:text-cyan-600"
                        >https://teddygat0r.vercel.app/</NuxtLink
                    >
                </p>
            </div>
        </div>
        <div class="hidden md:block"></div>
        <div class="hidden flex-col md:flex">
            <div><h4 class="font-bold">CLIENTS</h4></div>
            <div class="h-8"></div>
            <div class="text-gray-400">
                <p>
                    Web Design & Development<br />Mobile Application Development
                    <br />Digital Marketing Web <br />Application Development
                    <br />
                    Search Engine Optimization
                </p>
            </div>
        </div>
        <div class="hidden flex-col md:flex">
            <div><h4 class="font-bold">CONTACT US</h4></div>
        </div>
        <div class="hidden flex-col md:flex">
            <div><h4 class="font-bold">JOIN US</h4></div>
        </div>
    </footer>
</template>

<script setup lang="ts"></script>

<style scoped></style>
