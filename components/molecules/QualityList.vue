<template>
  <div class="v-full flex bg-green-500">
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
  name: "QualityList",
  components: { QualityCard },
  data() {
    return {
      qualities: [
        {
          title: "resilience et maintien",
          icon: "test",
          text: "Nos matelas s'adaptent au dormeur et non l'inverse !",
        },
        {
          title: "Matieres naturelles",
          icon: "test",
          text: "Nos matelas sont extrêmement respirants déhoussables, anti acariens et antibactériens ",
        },
        {
          title: "Economique et ecologique",
          icon: "test",
          text: "Des coûts optimisés grâce à une durée de vie double",
        },
        {
          title: "Prix reduits",
          icon: "test",
          text: "Des tarifs professionnels avantageux",
        },
        {
          title: "Un chargé de compte dédié",
          icon: "test",
          text: "Un accompagnement marketing sur-mesure",
        },
      ],
    };
  },
};
</script>
