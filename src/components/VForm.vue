<template>
  <div class="py-10 px-8">
    <h3 class="mb-6">Get in touch of the world</h3>
    <p class="mb-4">
      Your work is going to fill a large part of your life, and the only way to
      be truly satisfied.
    </p>
    <form class="w-full max-w-lg mx-auto">
      <div class="flex flex-wrap -mx-3 mb-6">
        <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0 relative">
          <input
            class="appearance-none block rounded leading-tight focus:outline-none w-full bg-gray-200 border py-3 px-4 mb-3 focus:bg-white"
            id="grid-first-name"
            type="text"
            required
          />
          <label class="absolute" for="grid-first-name">
            Enter your name
          </label>
          <p class="d-none text-red-500 text-xs italic">
            Please fill out this field.
          </p>
        </div>
        <div class="w-full md:w-1/2 px-3 relative">
          <input
            class="appearance-none block w-full bg-gray-200 border border-gray-200 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
            id="grid-last-name"
            type="email"
            required
          />
          <label class="absolute" for="grid-last-name"> Enter email </label>
          <p class="d-none text-red-500 text-xs italic">
            Please fill out this field.
          </p>
        </div>
      </div>
      <div class="flex flex-wrap -mx-3 mb-6">
        <div class="w-full px-3 relative">
          <input
            class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
            id="grid-password"
            type="text"
            required
          />
          <label class="absolute" for="grid-password">
            Enter your subject
          </label>
          <p class="d-none text-red-500 text-xs italic">
            Please fill out this field.
          </p>
        </div>
      </div>
      <div class="flex flex-wrap -mx-3 mb-8">
        <div class="w-full px-3 mb-6 md:mb-0 relative">
          <textarea
            class="appearance-none block w-full bg-gray-200 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
            id="grid-subject"
            type="text"
            required
          />
          <label class="absolute" for="grid-subject">
            Enter your subject
          </label>
          <p class="d-none text-red-500 text-xs italic">
            Please fill out this field.
          </p>
        </div>
      </div>
      <v-button text="Read more" class="text-blue-100 bg-blue-800 w-full" />
    </form>
  </div>
</template>

<script>
import VButton from "./VButton.vue";
export default {
  name: "VForm",
  components: { VButton },
};
</script>

<style scoped></style>
