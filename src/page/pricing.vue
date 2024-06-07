<script setup>
import Accordion from "../components/Accordion.vue";
</script>

<template>
  <section class="intro">
    <div class="container">
      <div class="text-center text-primary mt-44 md:mt-44 mb-12 md:mb-24">
        <h2 class="text-4xl font-semibold pb-4">Our Pricing Plans</h2>
        <p class="max-w-md mx-auto opacity-70">
          When you’re ready to go beyond prototyping in Figma, Webflow is ready
          to help you bring your designs to life — without coding them.
        </p>
      </div>
      <router-link to="/pricing"></router-link>
    </div>
  </section>

  <section>
    <div class="bg-gray-100 flex items-center justify-center py-10">
      <div class="bg-gray-50 p-6 rounded-xl shadow-md w-80">
        <div class="text-center flex items-center gap-2 pt-3">
          <div class="text-4xl font-bold p">$299</div>
          <div class="text-blue-600 text-lg">Per Design</div>
        </div>
        <div class="mt-6 pb-4">
          <h2 class="text-2xl font-semibold">Landing Page</h2>
          <p class="text-gray-600 mt-2">
            When you’re ready to go beyond prototyping in Figma,
          </p>
        </div>
        <ul class="mt-6 space-y-2">
          <li class="flex items-center text-gray-800">
            <svg
              class="w-4 h-4 text-green-500 mr-2"
              fill="currentColor"
              viewBox="0 0 20 20"
            >
              <path
                fill-rule="evenodd"
                d="M10 18a8 8 0 100-16 8 8 0 000 16zm-1.707-8.707a1 1 0 00-1.414 1.414L9 13.414l4.707-4.707a1 1 0 10-1.414-1.414L9 10.586l-1.707-1.707z"
                clip-rule="evenodd"
              />
            </svg>
            All limited links
          </li>
          <li class="flex items-center text-gray-800">
            <svg
              class="w-4 h-4 text-green-500 mr-2"
              fill="currentColor"
              viewBox="0 0 20 20"
            >
              <path
                fill-rule="evenodd"
                d="M10 18a8 8 0 100-16 8 8 0 000 16zm-1.707-8.707a1 1 0 00-1.414 1.414L9 13.414l4.707-4.707a1 1 0 10-1.414-1.414L9 10.586l-1.707-1.707z"
                clip-rule="evenodd"
              />
            </svg>
            Own analytics platform
          </li>
          <li class="flex items-center text-gray-800">
            <svg
              class="w-4 h-4 text-green-500 mr-2"
              fill="currentColor"
              viewBox="0 0 20 20"
            >
              <path
                fill-rule="evenodd"
                d="M10 18a8 8 0 100-16 8 8 0 000 16zm-1.707-8.707a1 1 0 00-1.414 1.414L9 13.414l4.707-4.707a1 1 0 10-1.414-1.414L9 10.586l-1.707-1.707z"
                clip-rule="evenodd"
              />
            </svg>
            Chat support
          </li>
          <li class="flex items-center text-gray-400">
            <svg
              class="w-4 h-4 text-gray-400 mr-2"
              fill="currentColor"
              viewBox="0 0 20 20"
            >
              <path
                fill-rule="evenodd"
                d="M10 18a8 8 0 100-16 8 8 0 000 16zm-1.707-8.707a1 1 0 00-1.414 1.414L9 13.414l4.707-4.707a1 1 0 10-1.414-1.414L9 10.586l-1.707-1.707z"
                clip-rule="evenodd"
              />
            </svg>
            Optimize hashtags
          </li>
          <li class="flex items-center text-gray-400">
            <svg
              class="w-4 h-4 text-gray-400 mr-2"
              fill="currentColor"
              viewBox="0 0 20 20"
            >
              <path
                fill-rule="evenodd"
                d="M10 18a8 8 0 100-16 8 8 0 000 16zm-1.707-8.707a1 1 0 00-1.414 1.414L9 13.414l4.707-4.707a1 1 0 10-1.414-1.414L9 10.586l-1.707-1.707z"
                clip-rule="evenodd"
              />
            </svg>
            Unlimited users
          </li>
        </ul>
        <button
          class="my-10 bg-gray-800 text-white py-2 px-12 rounded-full text-lg"
        >
          Get started
        </button>
      </div>
    </div>
  </section>

  <section class="Accordion">
    <div class="container mt-10 md:mt-20 mb-12 md:mb-24">
        <div class="flex flex-col md:flex-row md:justify-between">
          <div
            class="w-full md:w-[411px] mb-4 md:mb-0 text-center md:text-start"
          >
            <h2 class="text-[48px] font-semibold mb-4">
              Frequently asked questions
            </h2>
            <a class="opacity-80 text-base text-[#2405F2]" href="#"
              >Contact us For More Info</a
            >
          </div>
          <div class="w-full md:w-auto">
            <Accordion />
          </div>
        </div>
      </div>
  </section>
</template>

<style lang="scss" scoped></style>
