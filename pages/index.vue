<template>
  <div>
    <Header />
    <ResponsableProductSection />
    <BrandSection />
    <ProductSection />
  </div>
</template>

<script>
import Header from "@/components/organisms/Header.vue";
import BrandSection from "@/components/organisms/BrandSection.vue";
import ProductSection from "@/components/organisms/ProductSection.vue";
import ResponsableProductSection from "@/components/organisms/ResponsableProductSection.vue";
export default {
  name: "Index",
  components: {
    Header,
    BrandSection,
    ProductSection,
    ResponsableProductSection,
  },
};
</script>
