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

        <!-- Skill Section -->
        <section class="container mx-auto bg-base-200 min-h-screen">
            <div class="px-12 md:px-24 lg:px-40 py-6 md:py-6 lg:py-12">
                <h2 class="text-3xl font-bold mb-8">Work Experience</h2>
                <ul
                    class="timeline timeline-snap-icon max-md:timeline-compact timeline-vertical"
                >
                    <li>
                        <div class="timeline-middle">
                            <img
                                src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Google_2015_logo.svg/1200px-Google_2015_logo.svg.png"
                                alt=""
                                class="h-auto w-16"
                            />
                        </div>
                        <div class="timeline-start mb-10 md:text-end">
                            <time class="font-mono italic">1984</time>
                            <div class="text-lg font-black">
                                First Macintosh computer
                            </div>
                            The Apple Macintosh—later rebranded as the Macintosh
                            128K—is the original Apple Macintosh personal
                            computer. It played a pivotal role in establishing
                            desktop publishing as a general office function. The
                            motherboard, a 9 in (23 cm) CRT monitor, and a
                            floppy drive were housed in a beige case with
                            integrated carrying handle; it came with a keyboard
                            and single-button mouse.
                        </div>
                        <hr />
                    </li>
                    <li>
                        <hr />
                        <div class="timeline-middle">
                            <img
                                src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Google_2015_logo.svg/1200px-Google_2015_logo.svg.png"
                                alt=""
                                class="h-auto w-16"
                            />
                        </div>
                        <div class="timeline-end mb-10">
                            <time class="font-mono italic">1998</time>
                            <div class="text-lg font-black">iMac</div>
                            iMac is a family of all-in-one Mac desktop computers
                            designed and built by Apple Inc. It has been the
                            primary part of Apple's consumer desktop offerings
                            since its debut in August 1998, and has evolved
                            through seven distinct forms
                        </div>
                        <hr />
                    </li>
                    <li>
                        <hr />
                        <div class="timeline-middle">
                            <img
                                src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Google_2015_logo.svg/1200px-Google_2015_logo.svg.png"
                                alt=""
                                class="h-auto w-16"
                            />
                        </div>
                        <div class="timeline-start mb-10 md:text-end">
                            <time class="font-mono italic">2001</time>
                            <div class="text-lg font-black">iPod</div>
                            The iPod is a discontinued series of portable media
                            players and multi-purpose mobile devices designed
                            and marketed by Apple Inc. The first version was
                            released on October 23, 2001, about 8+1⁄2 months
                            after the Macintosh version of iTunes was released.
                            Apple sold an estimated 450 million iPod products as
                            of 2022. Apple discontinued the iPod product line on
                            May 10, 2022. At over 20 years, the iPod brand is
                            the oldest to be discontinued by Apple
                        </div>
                        <hr />
                    </li>
                    <li>
                        <hr />
                        <div class="timeline-middle">
                            <img
                                src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Google_2015_logo.svg/1200px-Google_2015_logo.svg.png"
                                alt=""
                                class="h-auto w-16"
                            />
                        </div>
                        <div class="timeline-end mb-10">
                            <time class="font-mono italic">2007</time>
                            <div class="text-lg font-black">iPhone</div>
                            iPhone is a line of smartphones produced by Apple
                            Inc. that use Apple's own iOS mobile operating
                            system. The first-generation iPhone was announced by
                            then-Apple CEO Steve Jobs on January 9, 2007. Since
                            then, Apple has annually released new iPhone models
                            and iOS updates. As of November 1, 2018, more than
                            2.2 billion iPhones had been sold. As of 2022, the
                            iPhone accounts for 15.6% of global smartphone
                            market share
                        </div>
                        <hr />
                    </li>
                    <li>
                        <hr />
                        <div class="timeline-middle">
                            <img
                                src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Google_2015_logo.svg/1200px-Google_2015_logo.svg.png"
                                alt=""
                                class="h-auto w-16"
                            />
                        </div>
                        <div class="timeline-start mb-10 md:text-end">
                            <time class="font-mono italic">2015</time>
                            <div class="text-lg font-black">Apple Watch</div>
                            The Apple Watch is a line of smartwatches produced
                            by Apple Inc. It incorporates fitness tracking,
                            health-oriented capabilities, and wireless
                            telecommunication, and integrates with iOS and other
                            Apple products and services
                        </div>
                    </li>
                </ul>
            </div>
        </section>
    </div>
</template>
