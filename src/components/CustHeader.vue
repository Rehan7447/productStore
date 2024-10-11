<template>
  <header class="header-test">
    <div class="container-test">
      <a href="/" class="logo-test">LOGO</a>
      <nav class="nav-test">
        <ul class="nav-links-test">
          <li><a href="/" class="link-test">Home</a></li>
          <li><a href="/products" class="link-test">Products</a></li>
          <li><a href="/checkout" class="link-test">Checkout</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style>

/* header */

.header-test {
  background-color: #333;
  padding: 20px 0;
}

.container-test {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  margin: 0 auto;
  padding: 0 20px;
}

.logo-test {
  color: white;
  text-decoration: none;
  font-size: 24px;
  font-weight: bold;
}

.nav-test .nav-links-test {
  list-style: none;
}

.nav-test .nav-links-test li {
  display: inline;
  margin-left: 30px;
}

.nav-test .nav-links-test li a {
  color: white;
  text-decoration: none;
  font-size: 18px;
}

.nav-test .nav-links-test li a:hover {
  text-decoration: underline;
}
</style>
