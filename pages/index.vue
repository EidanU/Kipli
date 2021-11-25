<template>
  <div class="text-green-800">
    <Header />
    <QualitySection />
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
import QualitySection from "@/components/organisms/QualitySection.vue";
export default {
  name: "Index",
  components: {
    Header,
    QualitySection,
    BrandSection,
    ProductSection,
    ResponsableProductSection,
  },
};
</script>
