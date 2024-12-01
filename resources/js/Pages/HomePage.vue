<script setup>
import { Head } from "@inertiajs/vue3";
import Navbar from "../Components/Navbar.vue";
</script>

<template>
    <Head title="Home" />
    <div>
        <!-- Navbar -->
        <Navbar />

        <!-- Hero Section -->
        <section class="container mx-auto bg-base-200 min-h-screen">
            <div class="hero px-6 md:px-24 lg:px-40 py-6 md:py-6 lg:py-12">
                <div
                    class="hero-content flex-col lg:flex-row-reverse items-center"
                >
                    <img
                        src="https://img.daisyui.com/images/stock/photo-1635805737707-575885ab0820.webp"
                        class="w-full max-w-sm rounded-lg shadow-2xl md:h-[400px] md:w-[400px]"
                    />
                    <div class="text-center lg:text-left mt-4 lg:mt-0 lg:mr-8">
                        <h1 class="text-5xl font-bold">Fihram Cahyo</h1>
                        <span class="text-2xl font-semibold"
                            >Full Stack Developer</span
                        >
                        <p class="py-6">
                            Provident cupiditate voluptatem et in. Quaerat
                            fugiat ut assumenda excepturi exercitationem quasi.
                            In deleniti eaque aut repudiandae et a id nisi.
                        </p>
                        <button class="btn btn-primary">Get Started</button>
                    </div>
                </div>
            </div>
        </section>

        <!-- Project Section -->
        <section class="container mx-auto bg-base-200 min-h-screen">
            <div class="px-12 md:px-24 lg:px-40 py-6 md:py-6 lg:py-12">
                <h2 class="text-3xl font-bold mb-8">Projects</h2>
                <div
                    class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-4 md:gap-4 lg:gap-6"
                >
                    <div
                        class="relative w-[150px] md:w-[180px] lg:w-[300px] h-[150px] md:h-[180px] lg:h-[300px] overflow-hidden rounded-lg"
                    >
                        <img
                            src="https://via.placeholder.com/300"
                            alt="Project 1"
                            class="w-[150px] md:w-[180px] lg:w-[300px] h-[150px] md:h-[180px] lg:h-[300px] object-cover rounded-lg transition duration-300 ease-in-out transform hover:scale-105"
                        />
                        <div
                            class="absolute inset-0 flex items-center justify-center opacity-0 bg-black bg-opacity-50 transition duration-300 ease-in-out hover:opacity-100"
                        >
                            <span class="text-white text-lg">Project 1</span>
                        </div>
                    </div>
                    <div
                        class="relative w-[150px] md:w-[180px] lg:w-[300px] h-[150px] md:h-[180px] lg:h-[300px] overflow-hidden rounded-lg"
                    >
                        <img
                            src="https://via.placeholder.com/300"
                            alt="Project 1"
                            class="w-[150px] md:w-[180px] lg:w-[300px] h-[150px] md:h-[180px] lg:h-[300px] object-cover rounded-lg transition duration-300 ease-in-out transform hover:scale-105"
                        />
                        <div
                            class="absolute inset-0 flex items-center justify-center opacity-0 bg-black bg-opacity-50 transition duration-300 ease-in-out hover:opacity-100"
                        >
                            <span class="text-white text-lg">Project 1</span>
                        </div>
                    </div>
                    <div
                        class="relative w-[150px] md:w-[180px] lg:w-[300px] h-[150px] md:h-[180px] lg:h-[300px] overflow-hidden rounded-lg"
                    >
                        <img
                            src="https://via.placeholder.com/300"
                            alt="Project 1"
                            class="w-[150px] md:w-[180px] lg:w-[300px] h-[150px] md:h-[180px] lg:h-[300px] object-cover rounded-lg transition duration-300 ease-in-out transform hover:scale-105"
                        />
                        <div
                            class="absolute inset-0 flex items-center justify-center opacity-0 bg-black bg-opacity-50 transition duration-300 ease-in-out hover:opacity-100"
                        >
                            <span class="text-white text-lg">Project 1</span>
                        </div>
                    </div>
                    <div
                        class="relative w-[150px] md:w-[180px] lg:w-[300px] h-[150px] md:h-[180px] lg:h-[300px] overflow-hidden rounded-lg"
                    >
                        <img
                            src="https://via.placeholder.com/300"
                            alt="Project 1"
                            class="w-[150px] md:w-[180px] lg:w-[300px] h-[150px] md:h-[180px] lg:h-[300px] object-cover rounded-lg transition duration-300 ease-in-out transform hover:scale-105"
                        />
                        <div
                            class="absolute inset-0 flex items-center justify-center opacity-0 bg-black bg-opacity-50 transition duration-300 ease-in-out hover:opacity-100"
                        >
                            <span class="text-white text-lg">Project 1</span>
                        </div>
                    </div>
                    <div
                        class="relative w-[150px] md:w-[180px] lg:w-[300px] h-[150px] md:h-[180px] lg:h-[300px] overflow-hidden rounded-lg"
                    >
                        <img
                            src="https://via.placeholder.com/300"
                            alt="Project 1"
                            class="w-[150px] md:w-[180px] lg:w-[300px] h-[150px] md:h-[180px] lg:h-[300px] object-cover rounded-lg transition duration-300 ease-in-out transform hover:scale-105"
                        />
                        <div
                            class="absolute inset-0 flex items-center justify-center opacity-0 bg-black bg-opacity-50 transition duration-300 ease-in-out hover:opacity-100"
                        >
                            <span class="text-white text-lg">Project 1</span>
                        </div>
                    </div>
                    <div
                        class="relative w-[150px] md:w-[180px] lg:w-[300px] h-[150px] md:h-[180px] lg:h-[300px] overflow-hidden rounded-lg"
                    >
                        <img
                            src="https://via.placeholder.com/300"
                            alt="Project 1"
                            class="w-[150px] md:w-[180px] lg:w-[300px] h-[150px] md:h-[180px] lg:h-[300px] object-cover rounded-lg transition duration-300 ease-in-out transform hover:scale-105"
                        />
                        <div
                            class="absolute inset-0 flex items-center justify-center opacity-0 bg-black bg-opacity-50 transition duration-300 ease-in-out hover:opacity-100"
                        >
                            <span class="text-white text-lg">Project 1</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skill Section -->
        <section class="container mx-auto bg-base-200 min-h-screen">
            <div class="px-12 md:px-24 lg:px-40 py-6 md:py-6 lg:py-12">
                <h2 class="text-3xl font-bold mb-8">Skills</h2>
                <!--  -->
            </div>
        </section>
    </div>
</template>
