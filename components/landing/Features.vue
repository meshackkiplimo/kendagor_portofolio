<script setup>
const certifications = [
  {
    title: "Certified Wildlife Biologist",
    description:
      "Recognized by The Wildlife Society for expertise in wildlife biology and management.",
    icon: "bx:bxs-badge-check",
  },
  {
    title: "Ecological Field Research",
    description:
      "Awarded certification for completing advanced field research methods in ecology.",
    icon: "bx:bxs-tree",
  },
  {
    title: "Conservation Leadership Program",
    description:
      "Certification for leading conservation projects in national parks and reserves.",
    icon: "bx:bxs-leaf",
  },
  {
    title: "Data Analysis in Ecology",
    description:
      "Certified in statistical and spatial data analysis for ecological studies.",
    icon: "bx:bxs-chart",
  },
  {
    title: "Habitat Restoration Specialist",
    description:
      "Certification for designing and implementing habitat restoration projects.",
    icon: "bx:bxs-home-heart",
  },
  {
    title: "Community Engagement in Conservation",
    description:
      "Trained in engaging local communities for effective and sustainable conservation.",
    icon: "bx:bxs-group",
  },
];
</script>

<template>
  <section class="bg-gray-50 py-16 px-6 lg:px-16">
    <div class="text-center">
      <h2 class="text-4xl lg:text-5xl font-bold text-green-900">
        My Certifications
      </h2>
      <p class="text-lg mt-4 text-gray-600 max-w-3xl mx-auto">
        Explore the certifications that demonstrate my expertise in wildlife biology, ecological research, and conservation leadership.
      </p>
    </div>

    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-10 mt-16">
      <div
        v-for="certification of certifications"
        :key="certification.title"
        class="bg-white shadow-lg rounded-lg p-6 transition-transform transform hover:scale-105"
      >
        <div class="flex items-center mb-4">
          <div class="bg-green-900 text-white rounded-full p-3 w-12 h-12 flex items-center justify-center">
            <Icon :name="certification.icon" class="text-2xl" />
          </div>
          <h3 class="ml-4 font-semibold text-lg text-green-900">
            {{ certification.title }}
          </h3>
        </div>
        <p class="text-gray-600">
          {{ certification.description }}
        </p>
      </div>
    </div>
  </section>
</template>

