<template>
  <div class="mt-5 h-auto bg-green-50 text-center p-3 shadow-xl rounded-md">
    <h2 class="text-xl font-bold">Obtenir un devis gratuit</h2>
    <p class="m-auto mb-5 text-sm w-9/12">
      Equipez votre établissement avec une literire saine, confortable et au
      prix juste :
    </p>
    <form class="w-full m-auto">
      <div class="w-9/12 flex m-auto mb-2 justify-between">
        <input
          type="text"
          required
          placeholder="Prenom"
          class="w-2/5 p-2 border-2 border-opacity-100 text-sm"
        />
        <input
          type="text"
          required
          placeholder="Nom"
          class="w-2/5 p-2 border-2 border-opacity-100 text-sm"
        />
      </div>
      <input
        type="email"
        required
        placeholder="Email"
        class="m-2 w-9/12 p-2 border-2 border-opacity-100 text-sm"
      />
      <input
        type="number"
        required
        placeholder="Téléphone"
        class="m-2 w-9/12 p-2 border-2 border-opacity-100 text-sm"
      />
      <input
        type="text"
        requiredb
        placeholder="Site Internet ou Entreprise"
        class="m-2 w-9/12 p-2 border-2 border-opacity-100 text-sm"
      />
      <textarea
        placeholder="Votre message"
        class="m-2 w-9/12 p-2 border-2 border-opacity-100 text-sm"
      >
      </textarea>
      <Button type="submit" value="Envoyer ma demande" />
    </form>
    <p class="text-blue-300 text-xs">Nous vous repondrons sous 48h</p>
  </div>
</template>
<script>
import Button from "@/components/atoms/Button.vue";
export default {
  name: "HeaderForm",
  components: { Button },
};
</script>
