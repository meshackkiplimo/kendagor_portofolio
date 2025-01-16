<template>
  <section class="py-12 " id="gallery">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-3xl font-bold text-green-900 mb-6 text-center">Gallery</h2>
      <p class="text-lg text-gray-700 text-center mb-10">
        Explore the amazing places I’ve visited, my work in community projects, and efforts in national parks and reserves.
      </p>

      <!-- Image Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Gallery Item -->
        <div v-for="item in galleryItems" :key="item.id" class="relative group">
          <img
            :src="item.image"
            :alt="item.title"
            class="w-full h-64 sm:h-80 md:h-96 object-cover rounded-lg shadow-lg"
          />
          <!-- Overlay -->
          <div
            class="absolute inset-0 bg-green-900 bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity duration-300 rounded-lg flex items-center justify-center text-center"
          >
            <p class="text-white text-sm font-semibold px-4">{{ item.title }}</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import hero1 from "/assets/img/hero2.jpg";

definePageMeta({
  layout: "landing",
});

export default {
  name: "Gallery",
  data() {
    return {
      galleryItems: [
        {
       
          title: "Research Project at Maasai Mara National Reserve",
          image: hero1
        },
        {
       
          title: "Community Conservation Project in Samburu",
          image: hero1,
        },
        {
          
          title: "Wildlife Tracking in Amboseli National Park",
          image: hero1,
        },
        {
        
          title: "Habitat Restoration at Tsavo East",
          image: hero1,
        },
        {
       
          title: "Biodiversity Study in Lake Nakuru National Park",
          image:hero1,
        },
        {
        
          title: "Engaging Local Communities in Mt. Kenya Region",
          image: hero1,
        },
      ],
    };
  },
};
</script>

<style scoped>
/* Optional: Add custom styles for hover effects */
.group:hover img {
  transform: scale(1.05);
  transition: transform 0.3s ease-in-out;
}
</style>
