<template>
  <div class="h-screen w-screen bg-gray-500">
    <HeadBar />
    <HeaderForm />
    <QualityList />
  </div>
</template>

<script>
import QualityList from "../molecules/QualityList.vue";
import HeaderForm from "../molecules/HeaderForm.vue";
import HeadBar from "../molecules/HeadBar.vue";
export default {
  name: "Header",
  components: {
    QualityList,
    HeaderForm,
    HeadBar,
  },
};
</script>
