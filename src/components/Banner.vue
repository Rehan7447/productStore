<template>
  <section class="banner-test">
    <div class="banner-content-test">
      <h1 class="banner-title-test">Welcome to The Test Site</h1>
      <p class="banner-description-test">
        Discovering the local street coding scene
      </p>
      <a href="/products" class="banner-button-test">Shop Now</a>
    </div>
  </section>
</template>

<style>
/* banner section */

.banner-test {
  background-image: url("https://via.placeholder.com/1200x400"); /* Replace with your image */
  background-size: cover;
  background-position: center;
  height: 400px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
  position: relative;
}

.banner-content-test {
  background-color: rgba(0, 0, 0, 0.5); /* Adds transparency */
  padding: 20px;
}

.banner-title-test {
  font-size: 48px;
  margin-bottom: 10px;
}

.banner-description-test {
  font-size: 24px;
  margin-bottom: 20px;
}

.banner-button-test {
  padding: 10px 20px;
  background-color: #ff6600;
  color: white;
  text-decoration: none;
  font-size: 18px;
  border-radius: 5px;
}

.banner-button-test:hover {
  background-color: #cc5200;
}
</style>
