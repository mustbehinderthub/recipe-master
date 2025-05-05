<template>
    <section class="section-spacing bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="heading-lg mb-4">
                    <span class="gradient-text">Popular Recipes</span>
                </h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                    Explore our most loved recipes that users create with ingredients they already have at home.
                </p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Recipe Card 1 -->
                <div class="bg-gray-800 rounded-xl overflow-hidden shadow-lg border border-gray-700 hover:border-teal-500 transition-all duration-300">
                    <div class="relative h-48 overflow-hidden">
                        <img src="https://via.placeholder.com/600x400/1a202c/14b8a6?text=Quick+Pasta+Dish" alt="Quick Pasta Dish" class="w-full h-full object-cover">
                        <div class="absolute top-0 right-0 bg-teal-500 text-white px-3 py-1 rounded-bl-lg">
                            <span class="text-sm font-medium">25 min</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-3">
                            <span class="text-sm text-teal-400">Italian</span>
                            <div class="flex items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-400" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <span class="text-sm text-gray-300 ml-1">4.8 (256)</span>
                            </div>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-2">Quick Pasta with Garlic & Oil</h3>
                        <p class="text-gray-300 mb-4 line-clamp-2">
                            A simple yet delicious pasta dish made with ingredients you likely already have in your pantry.
                        </p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-gray-700 text-gray-300 px-2 py-1 rounded-md text-xs">Pasta</span>
                            <span class="bg-gray-700 text-gray-300 px-2 py-1 rounded-md text-xs">Garlic</span>
                            <span class="bg-gray-700 text-gray-300 px-2 py-1 rounded-md text-xs">Olive Oil</span>
                            <span class="bg-gray-700 text-gray-300 px-2 py-1 rounded-md text-xs">Red Pepper</span>
                        </div>
                        <button class="w-full btn-primary">View Recipe</button>
                    </div>
                </div>
                
                <!-- Recipe Card 2 -->
                <div class="bg-gray-800 rounded-xl overflow-hidden shadow-lg border border-gray-700 hover:border-teal-500 transition-all duration-300">
                    <div class="relative h-48 overflow-hidden">
                        <img src="https://via.placeholder.com/600x400/1a202c/14b8a6?text=Vegetable+Stir+Fry" alt="Vegetable Stir Fry" class="w-full h-full object-cover">
                        <div class="absolute top-0 right-0 bg-teal-500 text-white px-3 py-1 rounded-bl-lg">
                            <span class="text-sm font-medium">20 min</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-3">
                            <span class="text-sm text-teal-400">Asian</span>
                            <div class="flex items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-400" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <span class="text-sm text-gray-300 ml-1">4.7 (189)</span>
                            </div>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-2">Quick Vegetable Stir Fry</h3>
                        <p class="text-gray-300 mb-4 line-clamp-2">
                            A versatile stir fry that works with whatever vegetables you have in your refrigerator.
                        </p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-gray-700 text-gray-300 px-2 py-1 rounded-md text-xs">Mixed Vegetables</span>
                            <span class="bg-gray-700 text-gray-300 px-2 py-1 rounded-md text-xs">Soy Sauce</span>
                            <span class="bg-gray-700 text-gray-300 px-2 py-1 rounded-md text-xs">Garlic</span>
                            <span class="bg-gray-700 text-gray-300 px-2 py-1 rounded-md text-xs">Ginger</span>
                        </div>
                        <button class="w-full btn-primary">View Recipe</button>
                    </div>
                </div>
                
                <!-- Recipe Card 3 -->
                <div class="bg-gray-800 rounded-xl overflow-hidden shadow-lg border border-gray-700 hover:border-teal-500 transition-all duration-300">
                    <div class="relative h-48 overflow-hidden">
                        <img src="https://via.placeholder.com/600x400/1a202c/14b8a6?text=Bean+Chili" alt="Bean Chili" class="w-full h-full object-cover">
                        <div class="absolute top-0 right-0 bg-teal-500 text-white px-3 py-1 rounded-bl-lg">
                            <span class="text-sm font-medium">40 min</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-3">
                            <span class="text-sm text-teal-400">Mexican</span>
                            <div class="flex items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-400" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <span class="text-sm text-gray-300 ml-1">4.9 (312)</span>
                            </div>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-2">Hearty Bean Chili</h3>
                        <p class="text-gray-300 mb-4 line-clamp-2">
                            A filling vegetarian chili that's perfect for using up canned beans and vegetables.
                        </p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-gray-700 text-gray-300 px-2 py-1 rounded-md text-xs">Beans</span>
                            <span class="bg-gray-700 text-gray-300 px-2 py-1 rounded-md text-xs">Tomatoes</span>
                            <span class="bg-gray-700 text-gray-300 px-2 py-1 rounded-md text-xs">Onion</span>
                            <span class="bg-gray-700 text-gray-300 px-2 py-1 rounded-md text-xs">Spices</span>
                        </div>
                        <button class="w-full btn-primary">View Recipe</button>
                    </div>
                </div>
            </div>
            
            <div class="mt-12 text-center">
                <Link :href="route('register')" class="btn-secondary">
                    View All Recipes
                </Link>
            </div>
        </div>
    </section>
</template>

<script setup>
import { Link } from '@inertiajs/vue3';
</script>
