<script setup>
definePageMeta({
  layout: "landing",
});
</script>

<template>
  <section class="py-16 bg-gray-50" id="about-me">
    <div class="max-w-7xl mx-auto px-6 lg:px-12 text-center lg:text-left">
      <h2 class="text-4xl font-extrabold text-green-900 mb-10">About Me</h2>
      <div class="grid lg:grid-cols-2 gap-12 items-center">
        <!-- Image Section -->
        <div class="flex justify-center">
          <img
            src="/assets/img/hero2.jpg"
            alt="Wildlife Biologist"
            class="rounded-full w-56 h-56 object-cover shadow-2xl transition-transform transform hover:scale-105"
          />
        </div>

        <!-- Text Section -->
        <div>
          <p class="text-lg text-gray-800 leading-relaxed mb-6">
            Hi, I’m <span class="font-semibold text-green-800">Kikie Kendagor</span>, a wildlife biologist and environmental researcher passionate about 
            preserving biodiversity and protecting ecosystems. With over <strong>5 years of experience</strong> in ecological studies, conservation efforts, 
            and wildlife management, I’m committed to making a positive difference in our world.
          </p>
          <p class="text-lg text-gray-800 leading-relaxed mb-6">
            I specialize in understanding animal behavior, monitoring species in their natural habitats, and driving sustainable practices to 
            ensure the survival of endangered species. I’ve had the privilege of working with conservation organizations, government bodies, and 
            local communities to make meaningful contributions to wildlife conservation.
          </p>
          <p class="text-lg text-gray-800 leading-relaxed mb-6">
            My approach combines <strong>field research</strong>, <strong>data-driven analysis</strong>, and <strong>policy advocacy</strong> to promote 
            sustainable ecosystems and innovative conservation strategies. I’m also passionate about educating others, sharing knowledge, 
            and inspiring action for a harmonious coexistence of wildlife and humanity.
          </p>
          <div class="mt-8">
            <a
              href="/contact"
              class="inline-block px-8 py-4 bg-green-600 text-white text-lg font-semibold rounded-lg shadow-md hover:bg-green-700 transform transition-all duration-300 hover:-translate-y-1"
            >
              Get in Touch
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AboutMe",
};
</script>

<style scoped>
/* Custom hover effect for smoother transitions */
img:hover {
  box-shadow: 0 8px 24px rgba(0, 128, 0, 0.2);
}
</style>
