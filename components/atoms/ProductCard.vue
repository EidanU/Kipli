<template>
  <div class="md:w-96 w-11/12 shadow-xl rounded-md lg:mt-0 mt-10">
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
        <fa icon="check" class="text-cutomText-blue mr-2" />
        {{ description }}
      </p>
      <p class="text-right text-sm text-cutomText-blue">
        A partir de
        <span class="font-bold text-xl">{{ price }} €</span>
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
