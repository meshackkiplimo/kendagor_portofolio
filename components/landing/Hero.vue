<template>
  <main class="relative bg-gray-100 py-16 lg:py-24">
    <div class="container mx-auto px-6 lg:px-16 grid lg:grid-cols-2 items-center gap-12">
      <!-- Left Section: Text -->
      <div class="text-center lg:text-left">
        <h1 class="text-4xl md:text-5xl lg:text-6xl font-extrabold text-green-900 leading-tight">
          Hello, I'm Kikie Kendagor
        </h1>
        <p class="text-lg mt-6 text-gray-700 max-w-2xl mx-auto lg:mx-0">
          I am a passionate wildlife biologist and environmental researcher dedicated to preserving biodiversity and advancing environmental science. Explore my journey through various projects, research, and initiatives that aim to protect and sustain ecosystems for future generations.
        </p>
        <div class="mt-8 flex justify-center lg:justify-start gap-4">
          <LandingLink
            href=""
            target="_blank"
            rel="noopener"
            class="bg-green-900 text-white px-6 py-3 rounded-lg shadow-lg hover:bg-green-800 transition cursor-pointer"
          >
            View My Resume
          </LandingLink>
          <LandingLink
            href="#gallery"
            class="bg-green-900 text-white border border-green-900 px-6 py-3 rounded-lg shadow-lg"
          >
            Explore My Work
          </LandingLink>
        </div>
      </div>

      <!-- Right Section: Image -->
      <div class="relative">
        <div class="rounded-full overflow-hidden shadow-lg hover:shadow-2xl transition-shadow">
          <img
            src="/assets/img/kend.jpg"
            alt="Kikie Kendagor"
            class="w-full h-auto"
          />
        </div>
        <!-- Decorative Ring -->
        <div class="absolute -top-6 -left-6 w-24 h-24 rounded-full border-4 border-green-900"></div>
        <div class="absolute -bottom-8 -right-8 w-32 h-32 rounded-full border-4 border-gray-300"></div>
      </div>
    </div>
  </main>
</template>
