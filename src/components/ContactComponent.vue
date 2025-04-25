<script setup>

</script>

<template>
  <div class="contact-section">
    <div class="contact-container">
      <div class="contact-image">
        <img src="@/assets/image7.jpg" alt="Nanny reading with children"/>
      </div>
      <div class="contact-form">
        <h4>Connect</h4>
        <h2>Get in Touch</h2>
        <p>We’d love to hear from you. Reach out!</p>

        <form>
          <label for="name">Name</label>
          <input type="text" id="name" placeholder="Your name" />

          <label for="email">Email</label>
          <input type="email" id="email" placeholder="Your email" />

          <label for="message">Message</label>
          <textarea id="message" placeholder="Type your message..."></textarea>

          <div class="terms">
            <input type="checkbox" id="terms" />
            <label for="terms">I accept the Terms</label>
          </div>

          <button type="submit">Submit</button>
        </form>
      </div>
    </div>
  </div>
</template>

<style scoped>
.contact-section {
  flex: 1;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 40px 20px;
}

.contact-container {
  background-color: #cc6b8e;
  display: flex;
  max-width: 1000px;
  width: 100%;
  border-radius: 20px;
  overflow: hidden;
  box-shadow: 0 4px 20px rgba(0,0,0,0.1);
}

.contact-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 20px 0 0 20px;
  max-height: 500px;
}

.contact-image {
  flex: 1;
}

.contact-form {
  flex: 1;
  padding: 40px;
  background-color: #cc6b8e;
  color: white;
}

.contact-form h4 {
  margin: 0;
  font-size: 14px;
  text-transform: uppercase;
}

.contact-form h2 {
  margin: 10px 0;
  font-size: 28px;
  font-weight: 600;
}

.contact-form p {
  margin-bottom: 30px;
  font-size: 14px;
  color: #f0e6ec;
}

.contact-form label {
  font-size: 12px;
  margin-bottom: 5px;
  display: block;
  color: #fff;
}

.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 12px;
  margin-bottom: 20px;
  border: none;
  border-radius: 8px;
  background-color: #e99ab5;
  color: #333;
  font-size: 14px;
}

.contact-form textarea {
  resize: none;
  height: 120px;
}

.terms {
  display: flex;
  align-items: center;
  margin-bottom: 20px;
  font-size: 12px;
  color: #fff;
}

.terms input {
  margin-right: 10px;
}

.contact-form button {
  padding: 10px 20px;
  border: none;
  background-color: white;
  color: black;
  font-weight: bold;
  border-radius: 8px;
  cursor: pointer;
  transition: background 0.3s;
}

.contact-form button:hover {
  background-color: #eee;
}

footer {
  background-color: #8b9bb7;
  padding: 40px 20px;
  text-align: center;
  color: white;
  font-size: 14px;
}

.footer-content {
  max-width: 1000px;
  margin: 0 auto;
}

.footer-top {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  margin-bottom: 20px;
}

.footer-top div {
  margin: 10px 20px;
}

.footer-links a {
  margin: 0 10px;
  color: white;
  text-decoration: none;
  font-size: 14px;
}

.footer-bottom {
  margin-top: 10px;
  font-size: 12px;
  color: #d1d9e6;
}

.social-icons {
  margin-top: 10px;
}

.social-icons a {
  margin: 0 5px;
  color: white;
  font-size: 16px;
  text-decoration: none;
}
</style>