<template>
  <div class="text-center">
    <h2 class="text-2xl font-bold m-5">Des produits responsables</h2>
    <p class="m-5">
      Aujourd'hui, 70% des voyaeurs sont plus susceptibles de reserver un
      hebergement ayant pris des mesures eco-responsables. Porposez une
      alternatives saine et durables ) vos hotes n adoptant la litterie Kipli !
    </p>
    <Button type="button" value="obtenir un devis" />
    <img
      src="https://kipli.com/_nuxt/img/Vege_P.a7b782a.svg"
      class="absolute w-16 right-0"
    />
  </div>
</template>
<script>
import Button from "@/components/atoms/Button.vue";
export default {
  name: "ResponsableProductSection",
  components: { Button },
};
</script>
