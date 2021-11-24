<template>
  <div class="w-80 h-96 bg-green-50 m-11 text-center">
    <h2>Obtenir un devis</h2>
    <p>
      Equipez votre etablissement avec une litterire saine,, onfortable et au
      prix juste
    </p>
    <form class="w-full bg-green-500 m-auto">
      <div class="w-9/12 flex bg-blue-500 m-auto justify-between">
        <input type="text" required placeholder="Prenom" class="w-2/5" />
        <input type="text" required placeholder="Nom" class="w-2/5" />
      </div>
      <input type="email" required placeholder="Email" class="m-2 w-9/12" />
      <input
        type="number"
        required
        placeholder="Téléphone"
        class="m-2 w-9/12"
      />
      <input
        type="text"
        requiredb
        placeholder="Site Internet ou Entreprise"
        class="m-2 w-9/12"
      />
      <textarea placeholder="Votre message" class="m-2 w-9/12"> </textarea>
      <input type="submit" value="Envoyer ma demande" class="m-2 w-9/12" />
    </form>
    <span>Nous vous repondrons sous 48h</span>
  </div>
</template>
<script>
export default {
  name: "HeaderForm",
};
</script>
