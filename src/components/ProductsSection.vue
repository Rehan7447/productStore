<script setup lang="ts">
import ProductCard from "./ProductCard.vue";
</script>

<template>
  <section class="products-page-section-test">
    <h2 class="products-page-title-test">Our Products</h2>
    <div class="product-grid-test">
      <!-- Product 1 -->
      <ProductCard />

      <!-- Product 2 -->
      <ProductCard />

      <!-- Product 3 -->
      <ProductCard />

      <!-- Product 4 -->
      <ProductCard />

      <!-- Product 5 -->
      <ProductCard />

      <!-- Product 6 -->
      <ProductCard />

      <!-- Product 7 -->
      <ProductCard />

      <!-- Product 8 -->
      <ProductCard />

      <!-- Product 9 -->
      <ProductCard />
    </div>
  </section>
</template>

<style>
/* Products Section */
.products-page-section-test {
  padding: 50px 20px;
  text-align: center;
  background-color: #fff;
}

.products-page-title-test {
  font-size: 32px;
  margin-bottom: 40px;
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
