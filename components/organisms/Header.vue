<template>
  <div
    class="h-screen w-screen bg-fixed"
    style="
      background-image: url('https://kipli.com/fr/wp-content/uploads/2021/10/matelas-home.jpg');
    "
  >
    <HeadBar />
    <HeaderForm />
  </div>
</template>

<script>
import HeaderForm from "../molecules/HeaderForm.vue";
import HeadBar from "../molecules/HeadBar.vue";
export default {
  name: "Header",
  components: {
    HeaderForm,
    HeadBar,
  },
};
</script>
