<template>
  <div class="product-card-test">
    <div class="product-image-test">
      <img src="https://via.placeholder.com/300x200" alt="Product Image" />
    </div>
    <div class="product-details-test">
      <h2 class="product-title-test">Product Name</h2>
      <p class="product-description-test">
        This is a short description of the product. It highlights key features
        and benefits.
      </p>
      <div class="product-price-test">$0</div>
      <button class="product-button-test">Add to Cart</button>
    </div>
  </div>
</template>

<style>
/* Product Card */
.product-card-test {
  background-color: white;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  max-width: 300px;
  margin: 20px auto;
  overflow: hidden;
  transition: transform 0.3s ease;
}

.product-card-test:hover {
  transform: translateY(-10px);
}

.product-image-test img {
  width: 100%;
  height: auto;
}

.product-details-test {
  padding: 20px;
  text-align: center;
}

.product-title-test {
  font-size: 22px;
  margin-bottom: 10px;
  color: #333;
}

.product-description-test {
  font-size: 14px;
  color: #777;
  margin-bottom: 15px;
}

.product-price-test {
  font-size: 20px;
  color: #e67e22;
  margin-bottom: 15px;
}

.product-button-test {
  padding: 10px 15px;
  background-color: #27ae60;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  font-size: 16px;
  transition: background-color 0.3s ease;
  cursor: pointer;
}

.product-button-test:hover {
  background-color: #2ecc71;
}
</style>
