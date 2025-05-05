<template>
    <section class="section-spacing bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col lg:flex-row items-center justify-between gap-12">
                <div class="lg:w-1/2">
                    <h1 class="heading-xl mb-6">
                        <span class="gradient-text">Recipe Master</span>
                        <span class="block text-white mt-2">Cook with what you have</span>
                    </h1>
                    <p class="text-xl text-gray-300 mb-8">
                        Discover delicious recipes based on ingredients you already have at home. 
                        No more wasted food or last-minute grocery runs.
                    </p>
                    <div class="flex flex-wrap gap-4">
                        <Link :href="route('register')" class="btn-primary">
                            Get Started
                        </Link>
                        <a href="#how-it-works" class="btn-secondary">
                            Learn More
                        </a>
                    </div>
                </div>
                <div class="lg:w-1/2">
                    <div class="relative">
                        <div class="absolute -inset-1 bg-gradient-to-r from-teal-500 to-green-500 rounded-lg blur-lg opacity-75"></div>
                        <div class="relative bg-gray-800 rounded-lg overflow-hidden shadow-xl">
                            <img src="/images/hero-image.jpg" alt="Recipe Master App" class="w-full h-auto" 
                                 onerror="this.src='https://via.placeholder.com/600x400/1a202c/14b8a6?text=Recipe+Master';this.onerror='';">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>
import { Link } from '@inertiajs/vue3';
</script>
