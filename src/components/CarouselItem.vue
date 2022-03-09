<template>
  <div class="carousel">
    <p><slot></slot></p>
    <img :src="slide" alt="" />
    <h4><slot></slot></h4>
    <p><slot></slot></p>
    <img src="./assets/images" alt="" />
  </div>
</template>

<script>
export default {
  name: "CarouselItem",
};
</script>

<style scoped></style>
