<template>
  <div class="w-96 shadow-xl rounded-md">
    <img :src="picture" />
    <div class="p-5">
      <div class="flex justify-between">
        <h3 class="text-xl font-bold mb-4">{{ title }}</h3>
        <div class="flex justify-between w-auto">
          <img
            src="https://kipli.com/_nuxt/img/made-in-france.5018fb1.png"
            class="w-8 h-8 mr-2"
          />
          <img
            src="https://kipli.com/_nuxt/img/pefc.c51635a.svg"
            class="w-8 h-8"
          />
        </div>
      </div>
      <p v-for="(description, index) in descriptions" :key="index">
        <fa icon="check" />
        {{ description }}
      </p>
      <p class="text-right text-xs text-green-200">
        A partir de
        <span class="font-bold text-sm">{{ price }} €</span>
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
