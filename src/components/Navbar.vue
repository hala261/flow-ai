<template>
    <nav class="fixed w-full z-20 top-0 border-b border-black/5">
    <div class="max-w-7xl flex items-center justify-between mx-auto p-4">

        <div class="flex items-center gap-2">
            <div class="w-8 h-8 flex items-center justify-center rounded-xl bg-indigo-500/90">
                <Workflow class="w-4 h-4 text-black" />
            </div>
            <span class="text-lg font-semibold whitespace-nowrap">FlowAI</span>
        </div>

        <div class="hidden md:block">
            <ul class="flex gap-8">
                <li>
                    <a class="text-sm font-medium text-black/70 hover:text-black" href="#">
                        Features
                    </a>
                </li>

                <li>
                    <a class="text-sm font-medium text-black/70 hover:text-black" href="#">
                        How It Works
                    </a>
                </li>

                <li>
                    <a class="text-sm font-medium text-black/70 hover:text-black" href="#">
                        Pricing
                    </a>
                </li>
            </ul>
        </div>      
        
        <div>
            <button type="button" class="bg-indigo-500/90 text-black text-sm px-3 py-2 rounded-xl">Get started</button>
        </div>

    </div>
    </nav>
</template>

<script setup>
import { Workflow } from '@lucide/vue';
</script>