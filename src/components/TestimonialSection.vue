<script setup>

</script>

<template>
  <section id="testimonial" class="bg-[var(--primary-medium)] testimonials-section scroll-mt-30">
    <h2>Testimonios</h2>
    <p>Escucha lo que dicen nuestros padres y niñeras satisfechos</p>
    <div class="grid">
      <div class="card">
        <img src="@/assets/image7.jpg" alt="Familia feliz">
        <p>"Nuestra niñera se convirtió en parte de la familia."</p>
      </div>
      <div class="card">
        <p>"Gracias a Softpulse encontré una niñera responsable y cariñosa."</p>
      </div>
      <div class="card">
        <div class="stars">★★★★★</div>
        <p>"Excelente servicio, súper fácil de usar."</p>
      </div>
      <div class="card">
        <p>"Me siento segura dejando a mis hijos con niñeras de Softpulse."</p>
      </div>
      <div class="card">
        <img src="@/assets/image8.jpg" alt="Niñera jugando">
        <p>"Las niñeras realmente se preocupan por los niños."</p>
      </div>
      <div class="card">
        <p>"La tranquilidad que necesitaba como madre soltera."</p>
      </div>
      <div class="card">
        <div class="stars">★★★★☆</div>
        <p>"Muy recomendable, encontré a mi niñera ideal."</p>
      </div>
      <div class="card">
        <img src="@/assets/image11.jpg" alt="Experiencia niñera">
        <p>"Gracias a Softpulse tengo trabajo constante como niñera."</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  color: white;
}

.testimonials-section {
  padding: 60px 20px;
  text-align: center;
}

.testimonials-section h2 {
  font-size: 36px;
  margin-bottom: 10px;
}

.testimonials-section p {
  font-size: 18px;
  margin-bottom: 40px;
  color: #1a1b1d;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  max-width: 1100px;
  margin: auto;
}

.card {
  background-color: #44558a;
  border-radius: 20px;
  padding: 20px;
  color: white;
  min-height: 180px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.card img {
  width: 60px;
  height: 60px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 10px;
}

.stars {
  color: gold;
  font-size: 20px;
  margin-bottom: 10px;
}

.card p {
  font-size: 16px;
}
</style>