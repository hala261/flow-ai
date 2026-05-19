<script setup>
import Navbar from '@/components/Navbar.vue';
import HeroSection from '@/components/HeroSection.vue';
import FeaturesSection from '@/components/FeaturesSection.vue';
import HowItWorksSection from '@/components/HowItWorksSection.vue';
import PricingSection from '@/components/PricingSection.vue';
import Footer from '@/components/Footer.vue';
</script>

<template>
    <div class="relative bg-[#131d31] text-white min-h-screen overflow-hidden">
        <Navbar />
        <HeroSection />
        <FeaturesSection />
        <HowItWorksSection />
        <PricingSection />
        <Footer />
    </div>
</template>

