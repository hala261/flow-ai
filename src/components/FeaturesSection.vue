<template>
  <section class="relative overflow-hidden">
    <div class="relative max-w-6xl mx-auto py-20 px-6">
        <div class="max-w-xl mb-20">
            <p class="text-sm text-indigo-500 font-medium tracking-wide uppercase">Features</p>
            <h2 class="mt-4 text-4xl md:text-5xl font-bold leading-tight max-w-xl">Everything you need to automate your workflow</h2>
            <p class="mt-6 text-lg text-slate-300 leading-relaxed">
                Key features to automate, integrate, and scale your workflow
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="rounded-2xl border border-white/10 bg-white/5 hover:bg-white/10 transition duration-300 p-8 min-h-45">
                <div class="flex items-center gap-2 mb-4">
                   <Zap class="w-5 h-5 text-indigo-500"/>
                   <h3 class="text-lg font-semibold">Instant Automation</h3>
                </div>
                <p class="mt-2 text-slate-400 text-sm leading-relaxed">
                    Automate repetitive tasks in seconds and eliminate manual work so your team can focus on what matters most
                </p>
            </div>

            <div class="rounded-2xl border border-white/10 bg-white/5 hover:bg-white/10 transition duration-300 p-8 min-h-45">
                <div class="flex items-center gap-2 mb-4">
                    <Workflow class="w-5 h-5 text-indigo-500"/>
                    <h3 class="text-lg font-semibold">Smart Integrations</h3>
                </div>
                <p class="mt-2 text-slate-400 text-sm leading-relaxed">
                    Connect all your favorite tools and apps into a single seamless workflow without any complexity
                </p>
            </div>

            <div class="rounded-2xl border border-white/10 bg-white/5 hover:bg-white/10 transition duration-300 p-8 min-h-45">
                <div class="flex items-center gap-2 mb-4">
                    <ChartColumn class="w-5 h-5 text-indigo-500"/>
                    <h3 class="text-lg font-semibold">Real-time Analytics</h3>
                </div>
                <p class="mt-2 text-slate-400 text-sm leading-relaxed">
                    Track performance and workflows in real time with clear insights that help you make better decisions
                </p>
            </div>
            
            <div class="rounded-2xl border border-white/10 bg-white/5 hover:bg-white/10 transition duration-300 p-8 min-h-45">
                <div class="flex items-center gap-2 mb-4">
                    <Shield class="w-5 h-5 text-indigo-500"/>
                    <h3 class="text-lg font-semibold">Secure & Scalable</h3>
                </div>
                <p class="mt-2 text-slate-400 text-sm leading-relaxed">
                    Enterprise-grade security and infrastructure designed to grow with your team safely and reliably
                </p>
            </div>
        </div>
    </div>
  </section>
</template>

<script setup>
import { Zap, Workflow, ChartColumn, Shield } from '@lucide/vue';
</script>