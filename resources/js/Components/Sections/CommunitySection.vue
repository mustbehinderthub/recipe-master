<template>
    <section class="section-spacing bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="heading-lg mb-4">
                    <span class="gradient-text">Join Our Community</span>
                </h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                    Connect with other home cooks, share recipes, and get inspired by what others are creating.
                </p>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                <!-- Testimonials -->
                <div>
                    <h3 class="text-2xl font-bold text-white mb-8">What Our Users Say</h3>
                    
                    <div class="space-y-8">
                        <!-- Testimonial 1 -->
                        <div class="bg-gray-800 rounded-xl p-6 border border-gray-700">
                            <div class="flex items-start">
                                <div class="flex-shrink-0 mr-4">
                                    <div class="h-12 w-12 rounded-full bg-gradient-to-r from-teal-500 to-green-500 flex items-center justify-center text-white font-bold">JD</div>
                                </div>
                                <div>
                                    <h4 class="text-lg font-semibold text-white">John D.</h4>
                                    <p class="text-gray-300 mt-2">
                                        "Recipe Master has completely changed how I cook. I used to waste so much food, but now I can easily find recipes that use what I already have."
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Newsletter -->
                <div>
                    <div class="bg-gray-800 rounded-xl p-8 border border-gray-700 mb-8">
                        <h3 class="text-2xl font-bold text-white mb-4">Stay Updated</h3>
                        <p class="text-gray-300 mb-6">
                            Subscribe to our newsletter for weekly recipe ideas, cooking tips, and community highlights.
                        </p>
                        <div class="flex flex-col sm:flex-row gap-4">
                            <input type="email" placeholder="Your email address" class="flex-grow px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg text-white">
                            <button class="btn-primary whitespace-nowrap">Subscribe</button>
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
