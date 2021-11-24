<template>
  <div class="w-80 h-96 bg-green-50 m-11">
    <h2>Obtenir un devis</h2>
    <p>
      Equipez votre etablissement avec une litterire saine,, onfortable et au
      prix juste
    </p>
    <form>
      <input type="text" required placeholder="Prenom" />
      <input type="text" required placeholder="Nom" />
      <input type="email" required placeholder="Email" />
      <input type="number" required placeholder="Téléphone" />
      <input type="text" required placeholder="Site Internet ou Entreprise" />
      <textarea placeholder="Votre message"> </textarea>
      <input type="submit" value="Envoyer ma demande" />
      <span>Nous vous repondrons sous 48h</span>
    </form>
  </div>
</template>
<script>
export default {
  name: "HeaderForm",
};
</script>
