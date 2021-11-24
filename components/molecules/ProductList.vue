<template>
  <div class="v-full flex bg-green-500">
    <ProductCard
      v-for="(product, index) in products"
      :key="index"
      v-bind:picture="product.picture"
      v-bind:title="product.title"
      v-bind:description="product.description"
      v-bind:price="product.price"
    />
  </div>
</template>
<script>
import ProductCard from "@/components/atoms/ProductCard.vue";
export default {
  name: "ProductList",
  components: { ProductCard },
  data() {
    return {
      products: [
        {
          picture: "picture",
          title: "Commode Picardie",
          description: ["bois de hêtre massif", "Latte flexibles ou rigides"],
          price: "700",
        },
        {
          picture: "picture",
          title: "Table de chevet Picardie",
          description: ["Epicéa massif", "Latte rigides"],
          price: "700",
        },
        {
          picture: "picture",
          title: "Etagère Picardie",
          description: ["bois de hêtre massif", "Latte flexibles ou rigides"],
          price: "700",
        },
      ],
    };
  },
};
</script>
