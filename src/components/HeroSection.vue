<script setup>

</script>

<template>
  <div class="bg-[var(--primary-darker)] text-white h-[470px] md:h-[700px]">
    <div class="max-w-[1900px] mx-auto px-10 h-full flex 2xl:px-50  flex-col md:flex-row items-center justify-between">
      <div class="md:w-1/2 mb-10 md:mb-0 text-left py-20 ">
        <h1 class="text-4xl md:text-5xl font-serif font-semibold mb-6 leading-tight">
          Find Trusted Babysitters Near You Today
        </h1>
        <p class="text-lg mb-6">
          Connecting parents with reliable babysitters has never been easier. Explore our platform
          to discover local caregivers who meet your family's needs.
        </p>
        <div class="space-x-4">
          <!--<button class="bg-white text-[#4e5c87] font-semibold px-5 py-2 rounded-full hover:bg-gray-100 transition">Learn More</button>-->
          <button class="border border-white px-5 py-2 rounded-full cursor-pointer hover:bg-[var(--primary-light)] hover:text-[#4e5c87]  transition">Sign Up</button>
        </div>
      </div>


      <div class="w-fit h-full flex overflow-hidden gap-4 rounded-lg">
        <div class="animate-slideUp">
          <div class="flex flex-col space-y-4">
            <img src="@/assets/image1.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image2.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image3.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image4.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image5.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image1.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image2.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image3.jpg" class="rounded-xl w-80 h-80 object-cover" />
          </div>
        </div>


        <div class="animate-slideDown">
          <div class="flex flex-col space-y-4">
            <img src="@/assets/image6.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image7.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image8.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image9.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image10.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image11.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image6.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image7.jpg" class="rounded-xl w-80 h-80 object-cover" />
            <img src="@/assets/image8.jpg" class="rounded-xl w-80 h-80 object-cover" />

          </div>
        </div>
      </div>
    </div>
  </div>

</template>

<style scoped>
@keyframes slideUp {
  0% {
    transform: translateY(0%);
  }
  100% {
    transform: translateY(-240%);
  }
}

.animate-slideUp {
  animation: slideUp 40s linear infinite;
}
@keyframes slideDown {
  0% {
    transform: translateY(-240%);
  }
  100% {
    transform: translateY(0%);
  }
}

.animate-slideDown {
  animation: slideDown 40s linear infinite;
}
</style>