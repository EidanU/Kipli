<template>
  <div class="w-1/4 bg-red-500 shadow">
    <div class="w-full h-10 bg-blue-500"></div>
    <!-- <div>{{ picture }}</div> -->
    <div class="p-5">
      <h3 class="text-xl font-bold">{{ title }}</h3>
      <p v-for="(description, index) in descriptions" :key="index">
        {{ description }}
      </p>
      <p class="text-right text-xs">
        A partir de <span class="font-bold text-sm">{{ price }}</span> €
      </p>
    </div>
  </div>
</template>
<script>
export default {
  name: "ProductCard",
  props: ["picture", "title", "descriptions", "price"],
};
</script>
