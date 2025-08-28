<script setup lang="ts">

</script>

<template>
  <div class="bg-gray-100 text-gray-800 font-sans">
  <!-- Navigation -->
  <nav class="bg-white shadow-md p-4 flex justify-between items-center sticky top-0 z-50">
    <h1 class="text-xl font-bold text-primary">INORA</h1>
    <div class="md:hidden">
      <button id="mobile-menu-button" class="text-dark focus:outline-none">
        <i class="fas fa-bars text-2xl"></i>
      </button>
    </div>
    <ul class="hidden md:flex gap-6">
      <li><a href="#home" class="hover:text-primary transition">Home</a></li>
      <li><a href="#about" class="hover:text-primary transition">About</a></li>
      <li><a href="#Hobbies & Skills" class="hover:text-primary transition">Hobbies & Skills</a></li>
      <li><a href="#projects" class="hover:text-primary transition">Achievements</a></li>
      <li><a href="#contact" class="hover:text-primary transition">Contact</a></li>
    </ul>

    <!-- Mobile Menu -->
    <div id="mobile-menu" class="absolute hidden top-16 left-0 w-full bg-white shadow-lg py-4">
      <ul class="flex flex-col items-center gap-4">
        <li><a href="#home" class="hover:text-primary transition">Home</a></li>
        <li><a href="#about" class="hover:text-primary transition">About</a></li>
        <li><a href="#skills" class="hover:text-primary transition">Skills</a></li>
        <li><a href="#projects" class="hover:text-primary transition">Projects</a></li>
        <li><a href="#contact" class="hover:text-primary transition">Contact</a></li>
      </ul>
    </div>
  </nav>

  <slot/>
  <!-- Footer -->

  </div>
</template>

<style scoped>

</style>