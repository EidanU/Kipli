<template>
  <div class="text-center h-96 mt-12">
    <h2 class="text-3xl font-bold m-5">Des produits responsables</h2>

    <!-- <img
      src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDI1LjIuMSwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkNhbHF1ZV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCIKCSB2aWV3Qm94PSIwIDAgNzY1LjEgMzUyIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA3NjUuMSAzNTI7IiB4bWw6c3BhY2U9InByZXNlcnZlIj4KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4KCS5zdDB7b3BhY2l0eTowLjU7ZmlsbDojRUNGMUVBO2VuYWJsZS1iYWNrZ3JvdW5kOm5ldyAgICA7fQo8L3N0eWxlPgo8cGF0aCBpZD0iVHJhY8OpXzMxNCIgY2xhc3M9InN0MCIgZD0iTTc0MSwzNi42QzYzMi45LTQ3LDExNC41LDI0LjIsNTcuMiwxMzNTLTk0LjEsMzg0LjgsMjQxLjcsMzQ1LjNTODQ5LjEsMTIwLjIsNzQxLDM2LjZ6Ii8+Cjwvc3ZnPgo="
      class="absolute right-1/2 left-1/2 w-96"
    /> -->
    <p class="m-auto my-10 w-3/5 text-xl">
      Aujourd'hui, 70% des voyageurs sont plus susceptibles de réserver un
      hébergement ayant pris des mesures éco-responsables. Proposez une
      alternative saine et durable à vos hotes en adoptant la literie Kipli !
    </p>
    <div class="w-96 m-auto">
      <Button type="button" value="Obtenir un devis" />
    </div>
    <img
      src="https://kipli.com/_nuxt/img/Vege_P.a7b782a.svg"
      class="absolute w-16 right-0 z-0"
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
