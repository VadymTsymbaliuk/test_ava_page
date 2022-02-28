<template>
  <header>
    <div>
      <nav class="container flex justify-between px-4 py-8 mx-auto bg-white">
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
        <div class="button-container">
          <button class="px-4 py-2 text-blue-100 bg-blue-800 rounded-full">
            Purchase template
          </button>
        </div>
        <div class="flex lg:hidden">
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
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "VHeader",
};
</script>

<style scoped></style>
