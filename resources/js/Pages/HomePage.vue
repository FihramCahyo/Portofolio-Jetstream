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
            <div class="hero px-4 py-8 md:px-36 md:py-12">
                <div
                    class="hero-content flex-col lg:flex-row-reverse items-center"
                >
                    <img
                        src="https://img.daisyui.com/images/stock/photo-1635805737707-575885ab0820.webp"
                        class=" w-full max-w-sm rounded-lg shadow-2xl  md:h-[400px] md:w-[400px]"
                    />
                    <div class="text-center lg:text-left mt-4 lg:mt-0 lg:mr-8">
                        <h1 class="text-5xl font-bold">Box Office News!</h1>
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
    </div>
</template>
