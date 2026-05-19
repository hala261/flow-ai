<template>
    <footer class="py-24 px-6 border-t border-white/10">
        <div class="max-w-6xl mx-auto flex flex-col md:flex-row justify-between gap-12 mb-6">
            <div class="max-w-sm">
                <h2 class="text-2xl font-bold mb-4">FlowAI</h2>
                <p class="text-sm text-slate-400 leading-relaxed">
                    Automate workflows, connect tools, and let AI handle repetitive work so your team can move faster
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 text-sm gap-10 mb-3">
                <div>
                    <h4 class="font-semibold mb-4">Product</h4>
                    <ul class="space-y-2 text-slate-400">
                        <li><a href="#" class="hover:text-white transition">Features</a></li>
                        <li><a href="#" class="hover:text-white transition">How It Works</a></li>
                        <li><a href="#" class="hover:text-white transition">Pricing</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="font-semibold mb-4">Company</h4>
                    <ul class="space-y-2 text-slate-400">
                        <li><a href="#" class="hover:text-white transition">About</a></li>
                        <li><a href="#" class="hover:text-white transition">Blog</a></li>
                        <li><a href="#" class="hover:text-white transition">Contact</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="font-semibold mb-4">Legal</h4>
                    <ul class="space-y-2 text-slate-400">
                        <li><a href="#" class="hover:text-white transition">Privacy</a></li>
                        <li><a href="#" class="hover:text-white transition">Terms</a></li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="max-w-6xl mx-auto flex flex-col md:flex-row justify-between items-center border-t border-white/10 gap-6 pt-5">
            <p class="text-sm text-slate-500">© 2026 FlowAI. All rights reserved.</p>
            <div class="flex items-center gap-5 text-slate-400">
                <a href="#" class="hover:text-white transition flex items-center">
                    <Icon icon="simple-icons:linkedin"/>
                </a>
                <a href="#" class="hover:text-white transition flex items-center">
                    <Icon icon="simple-icons:facebook"/>
                </a>
                <a href="#" class="hover:text-white transition flex items-center">
                    <Icon icon="simple-icons:x"/>
                </a>
                <a href="#" class="hover:text-white transition flex items-center">
                    <Icon icon="simple-icons:github"/>
                </a>
            </div>
        </div>
    </footer>
</template>

<script setup>
import { Icon } from '@iconify/vue';
</script>