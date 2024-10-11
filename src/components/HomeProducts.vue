<script setup lang="ts">
import ProductCard from "./ProductCard.vue";
</script>

<template>
  <section class="home-product-section-test">
    <h2 class="section-title-test">Featured Products</h2>
    <div class="product-grid-test">
      <ProductCard />
      <ProductCard />
      <ProductCard />
      <ProductCard />
    </div>
  </section>
</template>

<style>


/* Home Product Section */
.home-product-section-test {
  padding: 50px 20px;
  text-align: center;
  background-color: #fff;
}

.section-title-test {
  font-size: 28px;
  margin-bottom: 30px;
  color: #333;
}

/* Product Grid */
.product-grid-test {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  max-width: 1200px;
  margin: 0 auto;
}
</style>
