<script setup>

</script>

<template>
  <nav class="bg-[var(--primary-medium)] shadow-sm sticky top-0 z-50 w-full">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between items-center h-full">

        <div class="flex-shrink-0">
          <a href="/" class="text-xl font-bold text-[var(--primary-darker)]">
            <img src="@/assets/logo.png" alt="logo-image" class="w-40">
          </a>
        </div>


        <div class="hidden md:flex space-x-6">
          <a href="#features" class="text-gray-700 hover:text-[var(--pink)]">Features</a>
          <a href="#" class="text-gray-700 hover:text-[var(--pink)]">Benefits</a>
          <a href="#" class="text-gray-700 hover:text-[var(--pink)]">How It Works</a>
          <a href="#testimonial" class="text-gray-700 hover:text-[var(--pink)]">Testimonial</a>
          <a href="#contact" class="text-gray-700 hover:text-[var(--pink)]">Contact</a>
        </div>

        <div class="hidden md:flex">
          <a href="https://frontend-appweb.onrender.com" class="bg-[var(--primary-darker)] text-white px-4 py-2 rounded hover:bg-[var(--pink)]">Log In</a>
        </div>

      </div>
    </div>

  </nav>

</template>

<style scoped>

</style>