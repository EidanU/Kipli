<template>
  <div
    class="w-screen h-screen bg-fixed"
    style="
      background-image: url('https://kipli.com/fr/wp-content/uploads/2021/10/matelas-home.jpg');
    "
  >
    <HeadBar />
    <div class="w-96 m-11 pt-10">
      <img
        src="https://kipli.com/_nuxt/img/kipli.0987105.svg"
        class="w-52 m-auto"
      />
      <HeaderForm />
    </div>
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
