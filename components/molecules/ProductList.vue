<template>
  <div class="m-16">
    <h2 class="text-xl m-12 font-bold">Notre gamme</h2>
    <div class="v-full flex justify-between">
      <ProductCard
        v-for="(product, index) in products"
        :key="index"
        v-bind:picture="product.picture"
        v-bind:title="product.title"
        v-bind:descriptions="product.descriptions"
        v-bind:price="product.price"
      />
    </div>
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
          picture:
            "https://kipli.com/fr/wp-content/uploads/2021/10/69_113_10-min.jpg",
          title: "Commode Picardie",
          descriptions: ["bois de hêtre massif", "Latte flexibles ou rigides"],
          price: "700",
        },
        {
          picture:
            "https://kipli.com/fr/wp-content/uploads/2020/04/69_113_23-min-1.jpg",
          title: "Table de chevet Picardie",
          descriptions: ["Epicéa massif", "Latte rigides"],
          price: "700",
        },
        {
          picture:
            "https://kipli.com/fr/wp-content/uploads/2021/10/Normandie_6-min.jpg",
          title: "Etagère Picardie",
          descriptions: ["bois de hêtre massif", "Latte flexibles ou rigides"],
          price: "700",
        },
      ],
    };
  },
};
</script>
