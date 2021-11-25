<template>
  <div class="w-full flex justify-between bg-green-500">
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
          title: "resilience et maintien",
          iconLink: "@/static/confort.8edfb22.svg",
          text: "Nos matelas s'adaptent au dormeur et non l'inverse !",
        },
        {
          title: "Matieres naturelles",
          iconLink: "@/static/naturel.bfa3a54.svg",
          text: "Nos matelas sont extrêmement respirants déhoussables, anti acariens et antibactériens ",
        },
        {
          title: "Economique et ecologique",
          iconLink: "@/static/sain.21cd3d2.svg",
          text: "Des coûts optimisés grâce à une durée de vie double",
        },
        {
          title: "Prix reduits",
          iconLink: "@/static/service.5e4f5b5.svg",
          text: "Des tarifs professionnels avantageux",
        },
        {
          title: "Un chargé de compte dédié",
          iconLink: "@/static/service.5e4f5b5.svg",
          text: "Un accompagnement marketing sur-mesure",
        },
      ],
    };
  },
};
</script>
