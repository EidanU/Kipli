<template>
  <div class="w-1/4 bg-red-500 shadow">
    <img
      src="https://kipli.com/fr/wp-content/uploads/2021/10/69_113_10-min.jpg"
    />
    <div class="p-5">
      <div class="flex justify-between">
        <h3 class="text-xl font-bold">{{ title }}</h3>
        <div class="flex">
          <img
            src="https://kipli.com/_nuxt/img/made-in-france.5018fb1.png"
            class="w-8"
          />
          <img src="https://kipli.com/_nuxt/img/pefc.c51635a.svg" class="w-8" />
        </div>
      </div>
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
