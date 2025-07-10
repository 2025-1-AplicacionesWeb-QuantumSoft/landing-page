<script setup >
const videoId = 'LjGAmYckzvQ';
const videoId2 = 'cucT69I9tHs';
const videoUrl = `https://www.youtube.com/embed/${videoId}`;
const videoUrl2 = `https://www.youtube.com/embed/${videoId2}`;
</script>

<template>
  <section class="video-card-container ">
    <div class="card">
      <div class="video-wrapper">
        <iframe
            :src="videoUrl"
            title="Embedded YouTube Video"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
        ></iframe>
      </div>
      <div class="card-content">
        <h3 class="card-title">About the Product</h3>
      </div>
    </div>

    <div class="card">
      <div class="video-wrapper">
        <iframe
            :src="videoUrl2"
            title="Embedded YouTube Video"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
        ></iframe>
      </div>
      <div class="card-content">
        <h3 class="card-title">About de Team</h3>
      </div>
    </div>

  </section>
</template>

<style scoped>
.video-card-container {
  display: flex;
  justify-content: center;
  padding: 4rem 1rem;
  background: #f9fafb;
}

.card {
  background: white;
  border-radius: 1rem;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  max-width: 600px;
  margin-left: 2rem;
  width: 100%;
  transition: transform 0.3s ease;
}

.card:hover {
  transform: translateY(-5px);
}

.video-wrapper {
  position: relative;
  width: 100%;
  padding-bottom: 56.25%; /* 16:9 ratio */
}

.video-wrapper iframe {
  position: absolute;
  width: 100%;
  height: 100%;
  border: 0;
  top: 0;
  left: 0;
}

.card-content {
  padding: 1.5rem;
  text-align: center;
}

.card-title {
  font-size: 1.75rem;
  font-weight: bold;
  color: #1f2937;
  margin-bottom: 0.5rem;
}

.card-description {
  font-size: 1rem;
  color: #6b7280;
}
</style>