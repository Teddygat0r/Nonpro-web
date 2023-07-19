<template>
    <main class="flex flex-col">
        <div class="flex justify-center pt-8">
            <div
                class="my-auto flex w-[50%] flex-col justify-center gap-8 pb-[6%] pt-[5%] align-middle"
            >
                <div class="mx-auto">
                    <h1
                        class="line-height-increase text-4xl font-bold lg:text-6xl"
                    >
                        <span class="text-sky-400">Empowering</span> <br /><span
                            class="text-emerald-400"
                            >Nonprofits:</span
                        >
                        <br />One
                        <span class="text-yellow-300">Website</span> At <br />A
                        Time
                    </h1>
                </div>
                <div class="m-auto flex gap-8">
                    <button
                        class="text-white-300 rounded-md border-2 border-white px-8 py-3 font-bold transition duration-300 hover:border-sky-300 hover:text-sky-300"
                    >
                        Contact Me
                    </button>
                    <button
                        class="text-white-300 rounded-md bg-sky-500 px-8 py-3 font-bold transition duration-300 hover:bg-sky-600"
                    >
                        Contact Me
                    </button>
                </div>
            </div>
            <div class="flex w-[50%] flex-col justify-center text-center">
                <div class="relative h-[100%] rounded-l-3xl bg-green-300">
                    <div
                        class="absolute left-[40%] top-[10%] flex h-[80%] w-[400px] rounded-xl bg-gray-700"
                    >
                        <code
                            class="relative m-auto inline-block whitespace-pre-wrap text-start"
                            v-html="heroCode"
                        >
                        </code>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<script setup lang="ts">
const heroCode = `<span class="text-gray-400">&lt;</span><span class="text-pink-500">div</span> class="flex flex-col gap-4"<span class="text-gray-400">&gt;</span>
    <span class="text-gray-400">&lt;</span><span class="text-violet-400">h1</span><span class="text-gray-400">&gt;</span>Generating Templates...<span class="text-gray-400">&lt;</span><span class="text-violet-400">/h1</span><span class="text-gray-400">&gt;</span>
    <span class="text-gray-400">&lt;</span><span class="text-violet-400">p</span><span class="text-gray-400">&gt;</span>Filling text<span class="text-gray-400">&lt;</span><span class="text-violet-400">/p</span><span class="text-gray-400">&gt;</span>
    <span class="text-gray-400">&lt;</span><span class="text-violet-400">p</span><span class="text-gray-400">&gt;</span>Adding 
        <span class="text-gray-400">&lt;</span>span 
            class="<span class="text-emerald-400">text-emerald-400</span>"
            <span class="text-gray-400">&gt;</span><span class="italic text-emerald-400">Styles</span>
        <span class="text-gray-400">&lt;</span>/span<span class="text-gray-400">&gt;</span>
    <span class="text-gray-400">&lt;</span><span class="text-violet-400">/p</span><span class="text-gray-400">&gt;</span>
    <span class="text-gray-400">&lt;</span><span class="text-violet-400">p</span><span class="text-gray-400">&gt;</span>Finishing Touches<span class="text-gray-400">&lt;</span><span class="text-violet-400">/p</span><span class="text-gray-400">&gt;</span>
    <span class="text-gray-400">&lt;</span><span class="text-violet-400">p</span><span class="text-gray-400">&gt;</span>Applying SEO<span class="text-gray-400">&lt;</span><span class="text-violet-400">/p</span><span class="text-gray-400">&gt;</span>
<span class="text-gray-400">&lt;</span><span class="text-pink-500">/div</span><span class="text-gray-400">&gt;</span>`;
</script>

<style scoped>
.line-height-increase {
    line-height: 1.125;
}
</style>
