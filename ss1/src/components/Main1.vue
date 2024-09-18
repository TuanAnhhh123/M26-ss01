<template>
  <div class="main">
    <div class="grid">
      <cart-component v-for="n in 9" :key="n" />
    </div>
  </div>
</template>

<script>
import CartComponent from './Cart.vue';

export default {
  name: "Main",
  components: {
    CartComponent
  }
};
</script>

<style scoped>
.main {
  background-color: #ffe4e1;
  padding: 20px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}
</style>
