<template>
  <div
    class="w-screen h-screen bg-cover"
    style="
      background-image: url('https://kipli.com/fr/wp-content/uploads/2021/10/matelas-home.jpg');
    "
  >
    <HeadBar />
    <div class="md:w-96 w-4/5 m-auto md:m-11 md:pt-3 mt-10">
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
