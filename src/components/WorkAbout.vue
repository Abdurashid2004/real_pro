<script setup>
import { ref, reactive } from "vue";

// Initializing buttons array
const buttons = ref(["All", "UI Design", "Webflow Design", "Figma Design"]);

// Initializing active index to null
const activeIndex = ref(null);

// Function to set the active index
const func = (index) => {
  activeIndex.value = index;
};

const data = reactive([
  {
    img: "../src/assets/work.jpg",
    info: "Apparently we had reached a great height in the atmosphere, for the sky was a dead black, and the stars had ceased to twinkle.",
    btn: "View Portfolio",
  },
  {
    img: "../src/assets/work.jpg",
    info: "Apparently we had reached a great height in the atmosphere, for the sky was a dead black, and the stars had ceased to twinkle.",
    btn: "View Portfolio",
  },
  {
    img: "../src/assets/work.jpg",
    info: "Apparently we had reached a great height in the atmosphere, for the sky was a dead black, and the stars had ceased to twinkle.",
    btn: "Read case study",
  },
  {
    img: "../src/assets/work.jpg",
    info: "Apparently we had reached a great height in the atmosphere, for the sky was a dead black, and the stars had ceased to twinkle.",
    btn: "Read case study",
  },
  {
    img: "../src/assets/work.jpg",
    info: "Apparently we had reached a great height in the atmosphere, for the sky was a dead black, and the stars had ceased to twinkle. ",
    btn: "Read case study",
  },
  {
    img: "../src/assets/work.jpg",
    info: "Apparently we had reached a great height in the atmosphere, for the sky was a dead black, and the stars had ceased to twinkle.",
    btn: "Read case study",
  },
]);
</script>

<template>
  <div class="flex justify-center">
    <div class="container md:pt-[96px] pt-10 max-md:px-[5%]">
      <div class="flex md:gap-8 gap-4 max-md:grid grid-cols-2 justify-center">
        <button
          v-for="(item, index) in buttons"
          :key="index"
          @click="func(index)"
          :class="{
            change: activeIndex === index,
            'text-blackBlue': activeIndex !== index,
          }"
          class="md:text-lg"
        >
          {{ item }}
        </button>
      </div>

      <div
        class="md:grid grid-cols-2 gap-x-[34px] md:gap-y-10 mt-16 max-md:flex max-md:flex-wrap max-md:gap-4"
      >
        <div
          v-for="(item, index) in data"
          :key="index"
          class="text-blackBlue max-md:shadow-md"
        >
          <img :src="item.img" alt="img" class="w-full" />
          <div class="mt-6 max-md:px-4 max-md:pb-4">
            <h3 class="font-semibold text-3xl md:text-[38px]">
              Template {{ index + 1 }}
            </h3>
            <p class="mt-3 text-justify">{{ item.info }}</p>
            <div>
              <button class="cursor-pointer mt-6 font-medium">
                {{ item.btn }} &#8594;
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

.change {
  color: #2405f2;
}
</style>
