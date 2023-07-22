<template>
    <main class="flex flex-col overflow-x-hidden">
        <section
            id="hero"
            class="flex h-full flex-col justify-center pt-8 md:flex-row"
        >
            <div
                class="animate-fade-in my-auto flex flex-col justify-center gap-8 pb-[6%] pt-[5%] align-middle opacity-0 md:w-[50%]"
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
                <div class="buttons-fade-in-animation m-auto flex gap-8">
                    <button
                        class="text-white-300 rounded-md border-2 border-white px-8 py-3 font-bold transition duration-300 hover:border-sky-300 hover:text-sky-300"
                    >
                        Contact Us
                    </button>
                    <button
                        class="text-white-300 rounded-md bg-sky-500 px-8 py-3 font-bold transition duration-300 hover:bg-sky-600"
                    >
                        Join Us
                    </button>
                </div>
            </div>
            <div
                class="animate-enter-from-right flex transform flex-col justify-center text-center duration-1000 md:w-[50%] md:translate-x-full"
            >
                <div class="bg-waves-svg relative h-[100%] md:rounded-l-3xl">
                    <div
                        class="left-[40%] top-[10%] m-8 flex h-[80%] rounded-xl bg-gray-700 md:absolute md:m-0 md:w-[400px]"
                    >
                        <code
                            class="relative m-auto inline-block whitespace-pre-wrap p-4 text-start md:p-0"
                            v-html="heroCode"
                        >
                        </code>
                    </div>
                </div>
            </div>
        </section>
        <Branding></Branding>
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

@keyframes enter-from-right {
    0% {
        transform: translateX(100%);
        opacity: 0.5;
    }
    100% {
        transform: translateX(0);
        opacity: 1;
    }
}

.animate-enter-from-right {
    animation-name: enter-from-right;
    animation-duration: 3s;
    animation-fill-mode: forwards;
}

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

@keyframes buttons-fade-in {
    0% {
        opacity: 0;
        transform: translateY(-50%);
    }
    33% {
        opacity: 0;
        transform: translateY(-50%);
    }
    100% {
        opacity: 1;
        transform: translateY(0%);
    }
}

.buttons-fade-in-animation {
    animation-name: buttons-fade-in;
    animation-duration: 3s;
    animation-fill-mode: forwards;
}

.bg-waves-svg {
    background-image: url("/images/wavy_green_bg.svg");
    background-size: cover;
}
</style>
