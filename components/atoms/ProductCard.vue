<template>
  <div class="w-full">
    <p>test</p>
    <div>{{ picture }}</div>
    <h3>{{ title }}</h3>
    <p v-for="(description, index) in descriptions" :key="index">
      {{ description }}
    </p>
    <p>{{ price }}</p>
  </div>
</template>
<script>
export default {
  name: "ProductCard",
  props: ["picture", "title", "descriptions", "price"],
};
</script>
