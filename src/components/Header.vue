<template>
  <header>
    <section class="container">
      <nav class="flex justify-between px-4 py-8 mx-auto bg-white">
        <div>
          <img src="../assets/images/logo.png" alt="#" />
        </div>
        <div class="hidden space-x-8 lg:flex">
          <a href="">Home</a>
          <a href="">About Us</a>
          <a href="">Blogs</a>
          <a href="">Our Team</a>
          <a href="">Contact Us</a>
        </div>
        <v-button text="Purchase template" class="text-blue-100 bg-blue-800" />
        <div class="flex lg:hidden">
          <button
            class="menu inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-white hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-6 h-6"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M4 6h16M4 12h16M4 18h16"
              />
            </svg>
          </button>
        </div>
      </nav>
      <div class="mobile-menu flex hidden lg:hidden flex-col lg:flex">
        <a href="">Home</a>
        <a href="">About Us</a>
        <a href="">Blogs</a>
        <a href="">Our Team</a>
        <a href="">Contact Us</a>
      </div>
    </section>
  </header>
</template>

<script>
import VButton from "./VButton.vue";
export default {
  name: "VHeader",
  components: { VButton },
  mounted() {
    let buttonMenu = document.querySelector(".menu");

    buttonMenu.addEventListener("click", () => {
      document.querySelector(".mobile-menu").classList.toggle("hidden");
    });
  },
};
</script>

<style scoped></style>
