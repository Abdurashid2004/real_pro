<script setup>
import Accordion from "../components/Accordion.vue";
import Pricings from "../components/Pricings.vue";
</script>

<template>
  <section><Pricings /></section>

  <section class="Accordion">
    <div class="container mt-10 md:mt-20 mb-12 md:mb-24">
      <div class="flex flex-col md:flex-row md:justify-between">
        <div class="w-full md:w-[411px] mb-4 md:mb-0 text-center md:text-start">
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
