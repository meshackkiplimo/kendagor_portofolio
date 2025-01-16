<script setup>
definePageMeta({
  layout: "landing",
});
</script>


<template>
  <section class="py-12 " id="about-me">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <h2 class="text-3xl font-bold text-green-900 mb-6">About Me</h2>
      <div class="grid md:grid-cols-2 gap-8">
        <!-- Image Section -->
        <div class="flex justify-center items-center">
          <img
            src="/assets/img/hero2.jpg"
            alt="Wildlife Biologist"
            class="rounded-full w-48 h-48 object-cover shadow-lg"
          />
        </div>

        <!-- Text Section -->
        <div class="flex flex-col justify-center items-center md:items-start">
          <p class="text-lg text-gray-700 mb-4">
            Hello, I’m Kikie Kendagor, a dedicated wildlife biologist and environmental researcher with a passion for preserving
            biodiversity. With over 5 years of experience in ecological studies, conservation efforts, and wildlife management, I
            am committed to making a difference in the world by protecting our planet’s ecosystems.
          </p>
          <p class="text-lg text-gray-700 mb-4">
            I specialize in conducting research to understand animal behavior, monitoring species in their natural habitats, and
            contributing to sustainable practices that help ensure the survival of endangered species. Throughout my career, I’ve had
            the privilege of collaborating with conservation organizations, government agencies, and local communities to make a
            positive impact on wildlife conservation.
          </p>
          <p class="text-lg text-gray-700 mb-4">
            My work combines field research, data analysis, and policy advocacy to promote sustainable ecosystems and conservation
            strategies. I’m passionate about educating the public, sharing knowledge, and working towards a future where both wildlife
            and human communities can thrive.
          </p>
          <a
            href="#contact"
            class="inline-block mt-6 px-8 py-3 bg-green-600 text-white font-semibold rounded-lg shadow-lg hover:bg-green-700 transition-colors duration-300"
          >
            Contact Me
          </a>
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
/* Add custom styles if needed */
</style>
