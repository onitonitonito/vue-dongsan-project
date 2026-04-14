<template>
  <!-- Navigation Menu -->
  <div class="menu">
    <a v-for="작명 in 메뉴들" :key="작명">{{ 작명 }}</a>
  </div>

  <!-- Logo Section -->
  <div class="logo-wrapper">
    <img alt="Vue logo" src="./assets/logo-mario.png" class="logo">
  </div>

  <!-- Product List Section -->
  <div class="content">
    <div v-for="(p, i) in products" :key="i" class="product-item">
      <h4>{{ i+1 }}. {{ p }}</h4>
      <p>{{ prices[i] }}만원</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      메뉴들: ['Home', 'Shop', 'About'],
      products: ['역삼동원룸', '천호동원룸', '마포구원룸'],
      prices: [50, 60, 70],
    }
  }
}
</script>

<style>
/* Component specific styles can go here, but I'll focus on main.css for general design */
</style>
