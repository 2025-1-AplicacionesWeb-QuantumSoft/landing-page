<script setup>

</script>

<template>
  <section id="contact" class="w-full py-16 bg-gray-50">
    <div class="max-w-4xl mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-8">Contáctanos</h2>

      <div class="bg-white shadow-lg rounded-2xl p-8 space-y-8">
        <div class="flex items-center space-x-4">
          <div>
            <h3 class="text-xl font-semibold">¿Tienes preguntas?</h3>
            <p class="text-gray-600 text-sm max-w-md">Rellena el formulario y nos pondremos en contacto contigo lo antes posible.</p>
          </div>
        </div>

        <form class="grid grid-cols-1 md:grid-cols-2 gap-6">
          <div>
            <label class="block text-sm font-medium text-gray-700">Nombre</label>
            <input type="text" placeholder="Tu nombre" class="mt-1 w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-indigo-500">
          </div>

          <div>
            <label class="block text-sm font-medium text-gray-700">Apellido</label>
            <input type="text" placeholder="Tu apellido" class="mt-1 w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-indigo-500">
          </div>

          <div>
            <label class="block text-sm font-medium text-gray-700">Correo electrónico</label>
            <input type="email" placeholder="ejemplo@correo.com" class="mt-1 w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-indigo-500">
          </div>

          <div>
            <label class="block text-sm font-medium text-gray-700">Teléfono</label>
            <input type="text" placeholder="+51 999 999 999" class="mt-1 w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-indigo-500">
          </div>

          <div class="md:col-span-2">
            <label class="block text-sm font-medium text-gray-700">Mensaje</label>
            <textarea rows="4" placeholder="Escribe tu mensaje aquí..." class="mt-1 w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-indigo-500"></textarea>
          </div>
        </form>

        <div class="flex justify-end space-x-4 pt-4">
          <button class="bg-[var(--primary-darker)] text-white px-6 py-2 rounded-lg hover:bg-[var(primary-light)] transition">Enviar</button>
          <button type="reset" class="text-gray-600 hover:underline">Cancelar</button>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
</style>