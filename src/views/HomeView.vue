<script setup>

import Carousel from '../components/Carousel.vue'
import NavBar from '../components/NavBar.vue'

</script>

<template>
  <NavBar></NavBar>
  <Carousel></Carousel>
  <footer class="bg-gray-900 py-6 lg:py-8">
    <div
      class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col lg:flex-row justify-between items-center"
    >
      <div class="text-gray-400 text-sm lg:text-base">
        &copy; 2023 My Shoe Shop by Emir Efetürk. All rights reserved.
      </div>
    </div>
  </footer>
</template>

<style scoped></style>
