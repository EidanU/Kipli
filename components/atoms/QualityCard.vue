<template>
  <div class="w-full text-center m-2 bg-white">
    <p>{{ title }}</p>
    <img src="iconLink" />
    <p>{{ text }}</p>
  </div>
</template>
<script>
export default {
  name: "QualityCard",
  props: ["title", "iconLink", "text"],
};
</script>
