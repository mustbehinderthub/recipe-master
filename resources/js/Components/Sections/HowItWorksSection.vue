<template>
    <section id="how-it-works" class="section-spacing bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="heading-lg mb-4">
                    <span class="gradient-text">How It Works</span>
                </h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                    Recipe Master makes cooking with what you have simple and enjoyable. 
                    Follow these easy steps to get started.
                </p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Step 1 -->
                <div class="relative">
                    <div class="absolute -inset-1 bg-gradient-to-r from-teal-500 to-green-500 rounded-lg blur opacity-25"></div>
                    <div class="relative bg-gray-800 rounded-lg p-8 h-full">
                        <div class="flex items-center justify-center w-12 h-12 rounded-full bg-gradient-to-r from-teal-600 to-green-600 text-white font-bold text-xl mb-6">1</div>
                        <h3 class="text-xl font-bold text-white mb-4">Add Your Ingredients</h3>
                        <p class="text-gray-300">
                            Enter the ingredients you have in your kitchen. You can scan barcodes, 
                            manually add items, or import from your grocery delivery service.
                        </p>
                    </div>
                </div>
                
                <!-- Step 2 -->
                <div class="relative">
                    <div class="absolute -inset-1 bg-gradient-to-r from-teal-500 to-green-500 rounded-lg blur opacity-25"></div>
                    <div class="relative bg-gray-800 rounded-lg p-8 h-full">
                        <div class="flex items-center justify-center w-12 h-12 rounded-full bg-gradient-to-r from-teal-600 to-green-600 text-white font-bold text-xl mb-6">2</div>
                        <h3 class="text-xl font-bold text-white mb-4">Discover Recipes</h3>
                        <p class="text-gray-300">
                            Browse recipes that match your available ingredients. Filter by cuisine type, 
                            preparation time, dietary restrictions, and more.
                        </p>
                    </div>
                </div>
                
                <!-- Step 3 -->
                <div class="relative">
                    <div class="absolute -inset-1 bg-gradient-to-r from-teal-500 to-green-500 rounded-lg blur opacity-25"></div>
                    <div class="relative bg-gray-800 rounded-lg p-8 h-full">
                        <div class="flex items-center justify-center w-12 h-12 rounded-full bg-gradient-to-r from-teal-600 to-green-600 text-white font-bold text-xl mb-6">3</div>
                        <h3 class="text-xl font-bold text-white mb-4">Cook & Enjoy</h3>
                        <p class="text-gray-300">
                            Follow step-by-step instructions to prepare your meal. The app automatically 
                            updates your inventory as you use ingredients.
                        </p>
                    </div>
                </div>
            </div>
            
            <div class="mt-16 bg-gray-800 rounded-xl p-8 border border-gray-700">
                <div class="flex flex-col md:flex-row items-center">
                    <div class="md:w-2/3 mb-8 md:mb-0 md:pr-8">
                        <h3 class="text-2xl font-bold text-white mb-4">Ready to start cooking smarter?</h3>
                        <p class="text-gray-300 mb-6">
                            Join thousands of home cooks who are reducing food waste and discovering 
                            delicious new recipes with Recipe Master.
                        </p>
                        <Link :href="route('register')" class="btn-primary">
                            Create Free Account
                        </Link>
                    </div>
                    <div class="md:w-1/3">
                        <div class="bg-gray-700 rounded-lg p-6 text-center">
                            <div class="text-4xl font-bold text-white mb-2">30K+</div>
                            <p class="text-gray-300">Recipes Available</p>
                            
                            <div class="border-t border-gray-600 my-4"></div>
                            
                            <div class="text-4xl font-bold text-white mb-2">15K+</div>
                            <p class="text-gray-300">Active Users</p>
                            
                            <div class="border-t border-gray-600 my-4"></div>
                            
                            <div class="text-4xl font-bold text-white mb-2">4.8/5</div>
                            <p class="text-gray-300">User Rating</p>
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
