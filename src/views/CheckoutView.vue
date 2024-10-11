<script setup lang="ts">
import CustFooter from "@/components/CustFooter.vue";
import CustHeader from "@/components/CustHeader.vue";
</script>

<template>
  <CustHeader />
  <!-- Main Section for Checkout Page -->
  <main class="checkout-main-section-test">
    <div class="checkout-container-test">
      <!-- Left Section: Product List -->
      <div class="product-list-section-test">
        <h2 class="product-list-title-test">Your Products</h2>
        <div class="product-item-test">
          <div class="product-info-test">
            <h3 class="product-name-test">Product 1</h3>
            <p class="product-description-test">Description of Product 1.</p>
            <p class="product-price-test">$20.00</p>
          </div>
          <div class="product-quantity-test">
            <label for="quantity1">Quantity:</label>
            <input type="number" id="quantity1" value="1" min="1" />
          </div>
        </div>

        <div class="product-item-test">
          <div class="product-info-test">
            <h3 class="product-name-test">Product 2</h3>
            <p class="product-description-test">Description of Product 2.</p>
            <p class="product-price-test">$30.00</p>
          </div>
          <div class="product-quantity-test">
            <label for="quantity2">Quantity:</label>
            <input type="number" id="quantity2" value="1" min="1" />
          </div>
        </div>
      </div>

      <!-- Right Section: Checkout Details -->
      <div class="checkout-details-section-test">
        <h2 class="checkout-title-test">Checkout Details</h2>
        <div class="checkout-item-test">
          <p class="checkout-label-test">Subtotal:</p>
          <p class="checkout-price-test" id="subtotal">$50.00</p>
        </div>
        <div class="checkout-item-test">
          <p class="checkout-label-test">Tax:</p>
          <p class="checkout-price-test" id="tax">$5.00</p>
        </div>
        <div class="checkout-item-test">
          <p class="checkout-label-test">Total:</p>
          <p class="checkout-price-test" id="total">$55.00</p>
        </div>
        <button class="buy-button-test">Buy Now</button>
      </div>
    </div>
  </main>
  <CustFooter />
</template>

<style>
/* Checkout Main Section */
.checkout-main-section-test {
  display: flex;
  justify-content: center;
  padding: 40px;
  background-color: #f4f4f9;
  margin-bottom: 300px;
}

.checkout-container-test {
  display: flex;
  justify-content: space-between;
  width: 80%;
  max-width: 1200px;
  background-color: #fff;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  overflow: hidden;
}

/* Product List Section */
.product-list-section-test {
  flex: 2;
  padding: 25px;
  background-color: #fff;
}

.product-list-title-test {
  font-size: 28px;
  font-weight: 600;
  margin-bottom: 20px;
  color: #333;
}

.product-item-test {
  display: flex;
  justify-content: space-between;
  margin-bottom: 20px;
  padding-bottom: 15px;
  border-bottom: 1px solid #ececec;
}

.product-info-test {
  flex: 3;
}

.product-name-test {
  font-size: 22px;
  font-weight: 500;
  margin-bottom: 5px;
  color: #555;
}

.product-description-test {
  font-size: 16px;
  color: #777;
  margin-bottom: 8px;
}

.product-price-test {
  font-size: 18px;
  color: #e67e22;
  font-weight: bold;
}

/* Quantity Input Field Styling */
.product-quantity-test {
  flex: 1;
  display: flex;
  align-items: center;
}

.product-quantity-test label {
  font-size: 16px;
  color: #555;
  margin-right: 10px;
}

.product-quantity-test input {
  width: 80px;
  padding: 8px;
  border-radius: 5px;
  border: 1px solid #ddd;
  font-size: 16px;
  color: #333;
  text-align: center;
  box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.1);
}

/* Checkout Details Section */
.checkout-details-section-test {
  flex: 1;
  background-color: #fafafa;
  padding: 25px;
  border-left: 1px solid #ececec;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.checkout-title-test {
  font-size: 26px;
  font-weight: 600;
  margin-bottom: 20px;
  color: #333;
}

.checkout-item-test {
  display: flex;
  justify-content: space-between;
  margin-bottom: 15px;
}

.checkout-label-test {
  font-size: 18px;
  font-weight: 500;
  color: #666;
}

.checkout-price-test {
  font-size: 18px;
  color: #e67e22;
  font-weight: bold;
}

.buy-button-test {
  background-color: #e67e22;
  color: #fff;
  border: none;
  padding: 15px 25px;
  font-size: 18px;
  border-radius: 8px;
  cursor: pointer;
  transition: background-color 0.3s ease;
  margin-top: 20px;
}

.buy-button-test:hover {
  background-color: #d35400;
}

/* Media Query for Mobile */
@media (max-width: 768px) {
  .checkout-container-test {
    flex-direction: column;
  }

  .product-list-section-test,
  .checkout-details-section-test {
    width: 100%;
  }

  .product-quantity-test input {
    width: 60px;
  }
}
</style>
