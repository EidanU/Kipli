<template>
  <div class="h-screen w-screen bg-gray-50">
    <HeaderForm />
    <Qualities />
  </div>
</template>

<script>
import Qualities from "@/components/molecules/Qualities.vue";
import HeaderForm from "@/components/molecules/HeaderForm.vue";
export default {
  name: "Header",
  components: {
    Qualities,
    HeaderForm,
  },
};
</script>
