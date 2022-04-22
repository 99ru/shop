<template>
  <div class="product-list">
    <main>
      <div class="album py-5 bg-light">
        <div class="container">
          <div
            class="products-container row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-4"
          >
            <SingleProduct
              v-for="product in products"
              :key="product.id"
              :id="product.id"
              :name="product.name"
              :img="product.image_link"
              :price="product.price"
            />
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
import SingleProduct from "@/components/SingleProduct.vue";

export default {
  components: { SingleProduct },
  computed: {
    products() {
      return this.$store.getters.getProducts;
    },
  },
};
</script>
