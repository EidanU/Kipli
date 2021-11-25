<template>
  <div class="w-60 text-center m-2 bg-white inline-block">
    <h2 class="text-xl">{{ title }}</h2>
    <img class="m-auto my-5" src="@/static/confort.8edfb22.svg" />
    <p>{{ text }}</p>
  </div>
</template>
<script>
export default {
  name: "QualityCard",
  props: ["title", "iconLink", "text"],
};
</script>
