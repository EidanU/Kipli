<template>
  <div class="w-60 text-center">
    <h2 class="text-xl">{{ title }}</h2>
    <img class="m-auto my-5 w-12 h-12" :src="iconLink" />
    <p>{{ text }}</p>
  </div>
</template>
<script>
export default {
  name: "QualityCard",
  props: ["title", "iconLink", "text"],
};
</script>
