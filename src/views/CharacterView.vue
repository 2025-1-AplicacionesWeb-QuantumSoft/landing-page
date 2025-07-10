<template>
  <section id="features" class="bg-white py-16 px-4 sm:px-6 lg:px-8 scroll-mt-30">
    <div class="max-w-7xl mx-auto">
      <div class="text-center mb-16">
        <h1 class="text-4xl font-bold text-indigo-600 mb-4">Connect</h1>
        <h2 class="text-2xl font-semibold text-gray-800 mb-4">Your Local Nanny Network</h2>
        <p class="text-lg text-gray-600 max-w-2xl mx-auto">
          Find trusted nannies in your area with ease.
        </p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition-shadow flex flex-col opacity-0 animate-fade-in-up">

          <img src="../assets/image15.png" alt="Icono flexible" class="w-full h-48 object-cover rounded-t-lg">
          <h3 class="text-xl font-semibold text-gray-800 mb-2">Flexible</h3>
          <p class="text-gray-600 mb-4">Schedule Care on Your Terms</p>
          <p class="text-gray-500 mb-4 flex-grow">
            Easily manage your nanny's schedule with our interactive calendar.
          </p>
          <div class="mt-auto">
            <button class="text-indigo-600 font-medium hover:text-indigo-800 transition-colors">
              Join
            </button>
          </div>
        </div>
        <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition-shadow flex flex-col opacity-0 animate-fade-in-up">
          <img src="../assets/image10.jpg" alt="Icono confiable" class="w-full h-48 object-cover rounded-t-lg">
          <h3 class="text-xl font-semibold text-gray-800 mb-2">Reliable</h3>
          <p class="text-gray-600 mb-4">Read Reviews from Other Parents</p>
          <p class="text-gray-500 mb-4 flex-grow">
            See what others are saying about their experiences.
          </p>
          <div class="mt-auto">
            <button class="text-indigo-600 font-medium hover:text-indigo-800 transition-colors">
              Explore
            </button>
          </div>
        </div>
        <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition-shadow flex flex-col opacity-0 animate-fade-in-up">

          <div class="flex justify-center">
            <div class="text-4xl mb-4 w-20 h-20 flex items-center justify-center bg-indigo-100 rounded-full">👩‍👧</div>
          </div>
          <h3 class="text-xl font-semibold text-gray-800 mb-2">Personalized Nanny Profiles</h3>
          <p class="text-gray-600 mb-4">View detailed profiles to find the right fit.</p>
          <p class="text-gray-500 mb-4 flex-grow">
            Browse through comprehensive profiles with photos, experience, and skills.
          </p>
          <div class="mt-auto">
            <button class="text-indigo-600 font-medium hover:text-indigo-800 transition-colors">
              Browse
            </button>
          </div>
        </div>
        <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition-shadow flex flex-col opacity-0 animate-fade-in-up">

          <div class="flex justify-center">
            <div class="text-4xl mb-4 w-20 h-20 flex items-center justify-center bg-indigo-100 rounded-full">📅</div>
          </div>
          <h3 class="text-xl font-semibold text-gray-800 mb-2">Easy Booking Process</h3>
          <p class="text-gray-600 mb-4">Schedule your nanny with just a few clicks.</p>
          <p class="text-gray-500 mb-4 flex-grow">
            Our intuitive interface makes booking a nanny quick and simple.
          </p>
        </div>

        <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition-shadow flex flex-col opacity-0 animate-fade-in-up">

          <img src="../assets/image9.jpg" alt="Icono seguro" class="w-full h-48 object-cover rounded-t-lg">
          <h3 class="text-xl font-semibold text-gray-800 mb-2">Safe</h3>
          <p class="text-gray-600 mb-4">Your Peace of Mind Matters</p>
          <p class="text-gray-500 mb-4 flex-grow">
            Trust our community of vetted nannies to care for your children.
          </p>
          <div class="mt-auto">
            <button class="text-indigo-600 font-medium hover:text-indigo-800 transition-colors mr-4">
              Sign Up
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
  @keyframes fade-in-up {
    from {
      opacity: 0;
      transform: translateY(20px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  .animate-fade-in-up {
    animation: fade-in-up 0.8s ease-out forwards;
  }
</style>