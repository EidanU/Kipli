<template>
  <div class="quality">
    <QualityCard
      v-for="(quality, index) in qualities"
      :key="index"
      v-bind:icon="quality.icon"
      v-bind:text="quality.text"
      v-bind:title="quality.title"
    />
  </div>
</template>

<script>
import QualityCard from "@/components/atoms/QualityCard.vue";
export default {
  name: "Qualities",
  components: { QualityCard },
  data() {
    return {
      qualities: [
        { title: "title", icon: "test", text: "text" },
        { title: "title", icon: "test", text: "text 2" },
        { title: "title", icon: "test", text: "text 3" },
        { title: "title", icon: "test", text: "text 4" },
        { title: "title", icon: "test", text: "text 5" },
      ],
    };
  },
};
</script>

<style scoped>
.quality {
  width: 100%;
  display: flex;
  background: green;
}
</style>
