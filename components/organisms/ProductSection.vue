<template>
  <div class="w-full"><ProductList /> <Matelas /></div>
</template>
<script>
import ProductList from "../molecules/ProductList.vue";
import Matelas from "../molecules/Matelas.vue";
export default {
  name: "ProductSection",
  components: { ProductList, Matelas },
};
</script>
