<template>
  <div class="w-full text-center m-2 bg-white">
    <p>{{ title }}</p>
    <p>{{ icon }}</p>
    <p>{{ text }}</p>
  </div>
</template>
<script>
export default {
  name: "QualityCard",
  props: ["title", "icon", "text"],
};
</script>
