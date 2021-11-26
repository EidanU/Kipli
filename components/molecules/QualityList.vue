<template>
  <div class="mx-16 mt-12 flex justify-between">
    <QualityCard
      v-for="(quality, index) in qualities"
      :key="index"
      v-bind:iconLink="quality.iconLink"
      v-bind:text="quality.text"
      v-bind:title="quality.title"
    />
  </div>
</template>

<script>
import QualityCard from "@/components/atoms/QualityCard.vue";
export default {
  name: "QualityList",
  components: { QualityCard },
  data() {
    return {
      qualities: [
        {
          title: "Résilience et maintien",
          iconLink: "https://kipli.com/_nuxt/img/100nuits.f67536c.svg",
          text: "Nos matelas s'adaptent au dormeur et non l'inverse !",
        },
        {
          title: "Matieres naturelles",
          iconLink: "https://kipli.com/_nuxt/img/sain.21cd3d2.svg",
          text: "Nos matelas sont extrêmement respirants déhoussables, anti acariens et antibactériens ",
        },
        {
          title: "Economique et écologique",
          iconLink: "https://kipli.com/_nuxt/img/naturel.bfa3a54.svg",
          text: "Des coûts optimisés grâce à une durée de vie double",
        },
        {
          title: "Prix reduits",
          iconLink: "https://kipli.com/_nuxt/img/garantie.b84121b.svg",
          text: "Des tarifs professionnels avantageux",
        },
        {
          title: "Un chargé de compte dédié",
          iconLink: "https://kipli.com/_nuxt/img/client.6cebc10.svg",
          text: "Un accompagnement marketing sur-mesure",
        },
      ],
    };
  },
};
</script>
