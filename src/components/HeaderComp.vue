<template>
  <header>
    <div class="navbar navbar-dark bg-dark shadow-sm">
      <div class="container">
        <a href="#" class="navbar-brand d-flex align-items-center">
          <strong>My webshop.com</strong>
        </a>
        <CartComp />
      </div>
    </div>
  </header>
</template>

<script>
import CartComp from "@/components/CartComp.vue";
export default {
  components: { CartComp },
};
</script>
