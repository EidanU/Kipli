<template>
  <button class="m-2 w-56 p-1 bg-red-500 white text-white" type="type">
    {{ value }}
  </button>
</template>

<script>
export default { name: "Button", props: ["type", "value"] };
</script>
