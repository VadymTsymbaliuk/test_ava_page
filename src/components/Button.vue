<template>
  <button class="px-4 py-2 rounded-full">
    {{ text }}
  </button>
</template>

<script>
export default {
  name: "Button",
  props: {
    text: String,
  },
};
</script>

<style scoped></style>
