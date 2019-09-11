<template>
  <div class="container flex-col">
    <div
      class="bg-white flex flex-row justify-center mx-64 h-16 mb-20 border border-gray-500 rounded-lg"
    >
      <button
        class="flex flex-row focus:outline-none bg-transparent hover:bg-green-500 text-green-700 font-semibold hover:text-white py-2 px-4 border border-green-500 hover:border-transparent rounded"
      >
        <svg
          aria-hidden="true"
          focusable="false"
          data-prefix="fas"
          data-icon="plus"
          class="fill-current hover:text-white text-green-500 m-auto w-8 h-8"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 448 512"
        >
          <path
            fill="currentColor"
            d="M416 208H272V64c0-17.67-14.33-32-32-32h-32c-17.67 0-32 14.33-32 32v144H32c-17.67 0-32 14.33-32 32v32c0 17.67 14.33 32 32 32h144v144c0 17.67 14.33 32 32 32h32c17.67 0 32-14.33 32-32V304h144c17.67 0 32-14.33 32-32v-32c0-17.67-14.33-32-32-32z"
          />
        </svg>        
      </button>
      <input
        class="focus:outline-none py-2 px-4 block w-full rounded-lg"
        type="text"
        placeholder="Search"
      />
      <svg
        class="fill-current m-auto text-gray-500 w-8 h-8 mr-2"
        aria-hidden="true"
        focusable="false"
        data-prefix="fas"
        data-icon="search"
        role="img"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 512 512"
      >
        <path
          fill="currentColor"
          d="M505 442.7L405.3 343c-4.5-4.5-10.6-7-17-7H372c27.6-35.3 44-79.7 44-128C416 93.1 322.9 0 208 0S0 93.1 0 208s93.1 208 208 208c48.3 0 92.7-16.4 128-44v16.3c0 6.4 2.5 12.5 7 17l99.7 99.7c9.4 9.4 24.6 9.4 33.9 0l28.3-28.3c9.4-9.4 9.4-24.6.1-34zM208 336c-70.7 0-128-57.2-128-128 0-70.7 57.2-128 128-128 70.7 0 128 57.2 128 128 0 70.7-57.2 128-128 128z"
        />
      </svg>
    </div>
    <div class="flex flex-col">
      <div class="flex flex-row mb-6">
        <CardProject />
        <CardProject />
      </div>
      <!-- <div class="flex flex-row mb-6">
        <CardProject />
        <CardProject />
      </div>
      <div class="flex flex-row mb-6">
        <CardProject />
        <CardProject />
      </div>
      <div class="flex flex-row mb-6">
        <CardProject />
        <CardProject />
      </div>
      <div class="flex flex-row mb-6">
        <CardProject />
        <CardProject />
      </div>
      <div class="flex flex-row mb-6">
        <CardProject />
        <CardProject />
      </div>
      <div class="flex flex-row mb-6">
        <CardProject />
        <CardProject />
      </div>-->
    </div>
  </div>
</template>

<script>
import CardProject from "../../components/CardProject";

export default {
  components: {
    CardProject
  }
};
</script>