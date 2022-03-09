<template>
  <div class="slider" ref="slider">
    <div
      class="b-radius border-solid border-2 border-slate-100 mr-2 p-12 text-center"
    >
      <p>
        "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse
        varius enim in eros elementum tristique. "
      </p>
      <img
        src="../assets/images/sec-6/sec-6_img-1.png"
        alt="img-1"
        class="pb-4"
      />
      <h4>Martin Eduard</h4>
      <p>CEO of Marketing</p>
      <img src="../assets/images/sec-6/stars.png" alt="stars" />
    </div>
    <div
      class="b-radius border-solid border-2 border-slate-100 mr-2 p-12 text-center"
    >
      <p>
        "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse
        varius enim in eros elementum tristique. "
      </p>
      <img
        src="../assets/images/sec-6/sec-6_img-2.png"
        alt="img-1"
        class="pb-4"
      />
      <h4>Martin Eduard</h4>
      <p>CEO of Marketing</p>
      <img src="../assets/images/sec-6/stars.png" alt="stars" />
    </div>
    <div
      class="b-radius border-solid border-2 border-slate-100 mr-2 p-12 text-center"
    >
      <p>
        "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse
        varius enim in eros elementum tristique. "
      </p>
      <img
        src="../assets/images/sec-6/sec-6_img-3.png"
        alt="img-1"
        class="pb-4"
      />
      <h4>Martin Eduard</h4>
      <p>CEO of Marketing</p>
      <img src="../assets/images/sec-6/stars.png" alt="stars" />
    </div>
    <div
      class="b-radius border-solid border-2 border-slate-100 mr-2 p-12 text-center"
    >
      <p>
        "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse
        varius enim in eros elementum tristique. "
      </p>
      <img
        src="../assets/images/sec-6/sec-6_img-1.png"
        alt="img-1"
        class="pb-4"
      />
      <h4>Martin Eduard</h4>
      <p>CEO of Marketing</p>
      <img src="../assets/images/sec-6/stars.png" alt="stars" />
    </div>
    <div
      class="b-radius border-solid border-2 border-slate-100 mr-2 p-12 text-center"
    >
      <p>
        "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse
        varius enim in eros elementum tristique. "
      </p>
      <img
        src="../assets/images/sec-6/sec-6_img-2.png"
        alt="img-1"
        class="pb-4"
      />
      <h4>Martin Eduard</h4>
      <p>CEO of Marketing</p>
      <img src="../assets/images/sec-6/stars.png" alt="stars" />
    </div>
    <div
      class="b-radius border-solid border-2 border-slate-100 mr-2 p-12 text-center"
    >
      <p>
        "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse
        varius enim in eros elementum tristique. "
      </p>
      <img
        src="../assets/images/sec-6/sec-6_img-3.png"
        alt="img-1"
        class="pb-4"
      />
      <h4>Martin Eduard</h4>
      <p>CEO of Marketing</p>
      <img src="../assets/images/sec-6/stars.png" alt="stars" />
    </div>
  </div>
</template>

<script>
import $ from "jquery";

export default {
  name: "VCarousel",
  mounted() {
    $(".slider").slick({
      nextArrow: '<button type="button" class="slick-next"></button>',
      prevArrow: false,
      slidesToShow: 3,
      slidesToScroll: 1,
      responsive: [
        {
          breakpoint: 1024,
          settings: {
            slidesToShow: 3,
            infinite: true,
          },
        },
        {
          breakpoint: 600,
          settings: {
            slidesToShow: 2,
            dots: true,
          },
        },
        {
          breakpoint: 300,
          settings: "unslick", // destroys slick
        },
      ],
    });
  },
};
</script>

<style scoped></style>
