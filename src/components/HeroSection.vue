<template>
    <section class="relative isolate min-h-screen px-6">
        <div
            class="absolute -left-72 top-20
            w-212.5 h-212.5
            rounded-full
            bg-cyan-500/14
            blur-[120px]">
        </div>

        <div
            class="absolute left-1/2 top-1/2
            -translate-x-1/2 -translate-y-1/2
            w-250 h-250
            rounded-full
            bg-indigo-500/20
            blur-[120px]">
        </div>

        <div
            class="absolute -right-62.5 top-20
            w-212.5 h-212.5
            rounded-full
            bg-fuchsia-500/14
            blur-[120px]">
        </div>

        <div class="absolute bottom-0 left-0 w-full h-50 bg-black/15 blur-2xl"></div>

        <div class="relative z-10 max-w-5xl mx-auto h-screen flex flex-col items-center justify-center text-center gap-12">
            <h1 class="max-w-4xl text-5xl md:text-7xl font-bold">Automate your workflow in seconds</h1>
            <p class="max-w-2xl text-base md:text-lg text-slate-300">
                Connect your apps, automate repetitive work, and save hours every week
            </p>
            <div class="flex flex-col md:flex-row items-center justify-center gap-6">
                <button class="px-8 py-4 rounded-2xl bg-indigo-500 cursor-pointer hover:shadow-indigo-500/30 hover:scale-105 transition duration-300">Get Started</button>
                <button class="px-8 py-4 rounded-2xl border border-white/10 bg-white/5 cursor-pointer hover:bg-white/10 hover:border-white/20 transition">See How it Works</button>
            </div>
        </div>
    </section>
</template>