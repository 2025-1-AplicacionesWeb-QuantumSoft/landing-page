<script setup >
const videos = [
  {
    id: 1,
    url: "https://www.youtube.com/watch?v=cucT69I9tHs",
    caption: "About the Team"
  },
  {
    id: 2,
    url: "https://www.youtube.com/watch?v=LjGAmYckzvQ",
    caption: "About the Product"
  }
]
</script>

<template>
  <section class="video-section bg-[var(--primary-medium)]">
    <h2 class="video-title">Discover How KidyCare Works</h2>
    <div class="video-grid">
      <div class="video-container" v-for="video in videos" :key="video.id">
        <iframe
            :src="video.url"
            title="KidyCare Video"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
        ></iframe>
        <p class="video-caption">{{ video.caption }}</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.video-section {
  height: 600px;
  padding: 4rem 2rem;
  text-align: center;
}

.video-title {
  font-size: 2rem;
  font-weight: bold;
  margin-bottom: 2rem;
  color: #1f2937;
}

.video-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
}

.video-container {
  width: 100%;
  max-width: 500px;
}

.video-container iframe {
  width: 100%;
  height: 280px;
  border-radius: 1rem;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
}

.video-caption {
  margin-top: 0.75rem;
  font-size: 1rem;
  color: #4b5563;
}
</style>