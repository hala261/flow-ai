<template>
    <section class="py-24 px-6">
        <div class="max-w-6xl mx-auto">
            <div class="max-w-2xl mx-auto text-center mb-16">
                <p class="text-sm text-indigo-500 font-medium tracking-wide uppercase">Pricing</p>
                <h2 class="mt-3 text-4xl md:text-5xl font-bold leading-tight">Simple pricing for every team</h2>
                <p class="mt-5 text-lg text-slate-400">
                    Choose a plan that fits your workflow and scale as you grow
                </p>
            </div>
   
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">

                <!-- Starter -->

                <div class="rounded-2xl border border-white/10 bg-white/5 p-8 hover:bg-white/10 transition duration-300">
                    <div class="mb-6">
                        <h3 class="text-xl font-semibold mb-2">Starter</h3>
                        <p class="text-slate-400 text-sm">
                            Perfect for individuals getting started
                        </p>
                    </div>

                    <div class="mb-6">
                        <span class="text-4xl font-bold">$19</span>
                        <span class="text-slate-400">/month</span>
                    </div>

                    <ul class="space-y-3 text-sm text-slate-300">
                        <li>✔ Unlimited automations</li>
                        <li>✔ Basic integrations</li>
                        <li>✔ Email support</li>
                        <li>✔ Community support</li>
                    </ul>

                    <button class="mt-8 w-full rounded-xl bg-white/10 hover:bg-white/20 transition py-3 text-sm font-medium">
                        Get Started
                    </button>
                </div>

                <!-- Pro -->

                <div class="relative rounded-2xl border border-indigo-500/40 bg-indigo-500/10 p-8 hover:bg-indigo-500/15 transition duration-300">
                    <div class="absolute top-4 right-4 text-xs bg-indigo-500 px-3 py-1 rounded-full">Popular</div>
                    <div class="mb-6">
                        <h3 class="text-xl font-semibold mb-2">Pro</h3>
                        <p class="text-slate-300 text-sm">
                            Best for growing teams and businesses
                        </p>
                    </div>

                    <div class="mb-6">
                        <span class="text-4xl font-bold">$49</span>
                        <span class="text-slate-300">/month</span>
                    </div>

                    <ul class="space-y-3 text-sm text-slate-200">
                        <li>✔ Advanced automations</li>
                        <li>✔ Smart AI workflows</li>
                        <li>✔ Priority support</li>
                        <li>✔ Real-time analytics</li>
                    </ul>

                    <button class="mt-8 w-full rounded-xl bg-indigo-500 hover:bg-indigo-400 transition py-3 text-sm font-medium">
                        Start Free Trial
                    </button>
                </div>

                <!-- Enterprise -->
                 
                <div class="rounded-2xl border border-white/10 bg-white/5 p-8 hover:bg-white/10 transition duration-300">
                    <div class="mb-6">
                        <h3 class="text-xl font-semibold mb-2">Enterprise</h3>
                        <p class="text-slate-400 text-sm">
                            Built for large-scale organizations
                        </p>
                    </div>

                    <div class="mb-6">
                        <span class="text-3xl font-bold">Custom</span>
                    </div>

                    <ul class="space-y-3 text-sm text-slate-300">
                        <li>✔ Unlimited everything</li>
                        <li>✔ Dedicated infrastructure</li>
                        <li>✔ Enterprise security</li>
                        <li>✔ Dedicated account manager</li>
                    </ul>

                    <button class="mt-8 w-full rounded-xl bg-white/10 hover:bg-white/20 transition py-3 text-sm font-medium">
                        Contact Sales
                    </button>
                </div>
            </div>
        </div>
    </section>
</template>