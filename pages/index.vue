<template>
  <div>
    <Header />
    <BrandSection />
    <ProductSection />
  </div>
</template>

<script>
import Header from "@/components/organisms/Header.vue";
import BrandSection from "@/components/organisms/BrandSection.vue";
import ProductSection from "@/components/organisms/ProductSection.vue";
export default {
  name: "Index",
  components: {
    Header,
    BrandSection,
    ProductSection,
  },
};
</script>
