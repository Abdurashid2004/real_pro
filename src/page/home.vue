<template>
  <!-- =========================================== INTRO ========================================== -->
  <div class="pb-12 lg:pb-28 pt-8 lg:pt-20 bg-[#1C1E53] outline-none">
    <div
      class="container pt-16 lg:pt-24 flex flex-col lg:flex-row justify-between items-center md:mt-1 mt-20"
    >
      <div class="w-full lg:w-[60%] max-w-[495px] text-center md:text-start">
        <h1 class="text-4xl lg:text-5xl text-white font-semibold pb-6">
          Building stellar websites for early startups
        </h1>
        <p class="text-lg lg:text-base font-medium text-white opacity-70 pb-6">
          Lorem ipsum dolor sit, consectetur adipiscing elit. Lorem ipsum dolor
          sit, consectetur adipiscing elit. Eiusmod tempor incididunt.
        </p>
        <div
          class="pt-6 lg:pt-14 flex lg:flex-row md:gap-4 max-md:justify-between"
        >
          <router-link to="/work">
            <button
              class="font-medium rounded-3xl px-10 py-3 lg:py-4 lg:px-10 bg-[#FCD980] text-[#1B1C2B] hover:text-white transition duration-300 ease-in-out"
            >
              View our work
            </button>
          </router-link>
          <div class="flex items-center gap-2 cursor-pointer">
            <a href="/pricing" class="font-medium text-white">View Pricing</a>
            <span class="mt-1">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="2em"
                height="1.5em"
                viewBox="0 0 32 32"
                fill="currentColor"
              >
                <path
                  d="M21.188 9.281L19.78 10.72L24.063 15H4v2h20.063l-4.282 4.281l1.407 1.438L27.905 16z"
                  fill="white"
                />
              </svg>
            </span>
          </div>
        </div>
      </div>
      <div class="mt-8 max-w-[695px] lg:mt-0">
        <div class="aspect-w-16">
          <img src="../assets/intro.png" alt="image" class="" />
        </div>
      </div>
    </div>
  </div>

  <!-- ===================================== OurWork =============================================== -->

  <section>
    <div class="container">
      <div
        class="flex flex-col md:flex-row justify-between mt-[45px] md:mt-[57px] mb-[64px]"
      >
        <div>
          <h2 class="text-4xl font-semibold">View our projects</h2>
        </div>
        <div
          class="flex items-center gap-2 text-primary font-medium cursor-pointer mt-4 md:mt-0"
        >
          <h3 class="text-lg">View More</h3>
          <span>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="1.5em"
              height="1.5em"
              viewBox="0 0 32 32"
            >
              <path
                fill="black"
                d="M21.188 9.281L19.78 10.72L24.063 15H4v2h20.063l-4.282 4.281l1.407 1.438L27.905 16z"
              />
            </svg>
          </span>
        </div>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-5 mt-8">
        <div
          class="col-span-1 md:col-span-2 row-span-2 relative overflow-hidden group"
        >
          <div
            class="w-1/2 absolute top-0 duration-300 group-hover:left-0 -left-full h-full bg-gradient-to-br from-[#1C1E536B]/40 to-[#1C1E53] px-8 pt-[30px] md:pt-[200px] text-xs"
          >
            <h2 class="md:text-3xl font-semibold   text-white w-[340px]">
              Workhub office Webflow Webflow Design
            </h2>
            <p class="text-[16px] text-white mt-[16px] mb-[40px]"> 
              Euismod faucibus turpis eu gravida mi. Pellentesque et velit
              aliquam
            </p>
            <div class="flex items-center gap-3 mb-20 cursor-pointer">
              <a class="text-base font-lg text-[#FCD980]" href="/">
                View project
              </a>
              <span>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1.5em"
                  height="1.5em"
                  viewBox="0 0 32 32"
                >
                  <path
                    fill="#FCD980"
                    d="M21.188 9.281L19.78 10.72L24.063 15H4v2h20.063l-4.282 4.281l1.407 1.438L27.905 16z"
                  />
                </svg>
              </span>
            </div>
          </div>
          <img
            class="w-full h-full object-cover"
            src="../assets/Card.jpg"
            alt="Workhub office Webflow Webflow Design"
          />
        </div>
        <div class="col-span-1 relative overflow-hidden group">
          <div
            class="w-full absolute top-0 duration-300 group-hover:left-0 -left-full h-full bg-gradient-to-br from-[#1C1E536B]/40 to-[#1C1E53] px-8 pt-[108px] md:pt-[100px]"
          >
            <h2 class="text-3xl font-semibold text-white w-[320px]">
              Unisaas Website Design
            </h2>
            <div class="flex items-center gap-3 mt-4">
              <a class="text-base font-medium text-[#FCD980]" href="/">
                View project
              </a>
              <span>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1.5em"
                  height="1.5em"
                  viewBox="0 0 32 32"
                >
                  <path
                    fill="#FCD980"
                    d="M21.188 9.281L19.78 10.72L24.063 15H4v2h20.063l-4.282 4.281l1.407 1.438L27.905 16z"
                  />
                </svg>
              </span>
            </div>
          </div>
          <img
            class="w-full h-full object-cover"
            src="../assets/Rectangle 1313.jpg"
            alt="Unisaas Website Design"
          />
        </div>
        <div class="col-span-1 relative overflow-hidden group">
          <div
            class="w-full absolute top-0 duration-300 group-hover:left-0 -left-full h-full bg-gradient-to-br from-[#1C1E536B]/40 to-[#1C1E53] px-8 pt-[138px] md:pt-[100px]"
          >
            <h2
              class="text-3xl font-semibold text-white justify-center w-[320px]"
            >
              Unisaas Website Design
            </h2>
            <div class="flex items-center gap-3 mt-4">
              <a class="text-base font-medium text-[#FCD980]" href="/">
                View project
              </a>
              <span>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1.5em"
                  height="1.5em"
                  viewBox="0 0 32 32"
                >
                  <path
                    fill="#FCD980"
                    d="M21.188 9.281L19.78 10.72L24.063 15H4v2h20.063l-4.282 4.281l1.407 1.438L27.905 16z"
                  />
                </svg>
              </span>
            </div>
          </div>
          <img
            class="w-full h-full object-cover"
            src="../assets/Card (1).jpg"
            alt="Additional Project Image"
          />
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================== Cards ================================================= -->

  <section>
    <div id="app" class="bg-[#F4F6FC] pb-32">
      <div class="container mt-[60px] md:mt-[120px]">
        <h3 class="text-xl font-semibold mb-2 pt-14 text-center">Features</h3>
        <h2
          class="text-[48px] font-bold text-center max-w-[610px] mx-auto mb-14"
        >
          Design that solves problems, one product at a time
        </h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
          <div
            v-for="(item, index) in items"
            :key="index"
            class="feature-item pl-10 border bg-white border-white h-[336px] flex-col items-center justify-between hover:shadow-md hover:shadow-slate-400"
          >
            <img class="mt-8" :src="item.icon" alt="" />
            <div class="mt-12 w-[324px]">
              <h3 class="text-2xl font-medium mb-4 text-[#282938]">
                {{ item.name }}
              </h3>
              <p class="text-lg text-[#282938] opacity-70">{{ item.text }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- clients -->

  <section>
    <Testimonials />
  </section>

  <router-link to="/"></router-link>
</template>

<script setup>
import Testimonials from "../components/Testimonials.vue";

const items = [
  {
    icon: "../src/assets/icons.png",
    name: "User-Friendly Interface",
    text: "Euismod faucibus turpis eu gravida mi. Pellentesque et velit aliquam sed faucib turpis eu gravida mi. Pellentesque et velit aliquam sed mi. ",
  },
  {
    icon: "../src/assets/icons.png",
    name: "High Performance",
    text: "Euismod faucibus turpis eu gravida mi. Pellentesque et velit aliquam sed faucib turpis eu gravida mi. Pellentesque et velit aliquam sed mi. ",
  },
  {
    icon: "../src/assets/icons.png",
    name: "Robust Security",
    text: "Euismod faucibus turpis eu gravida mi. Pellentesque et velit aliquam sed faucib turpis eu gravida mi. Pellentesque et velit aliquam sed mi. ",
  },
  {
    icon: "../src/assets/icons.png",
    name: "Customizable Settings",
    text: "Euismod faucibus turpis eu gravida mi. Pellentesque et velit aliquam sed faucib turpis eu gravida mi. Pellentesque et velit aliquam sed mi. ",
  },
  {
    icon: "../src/assets/icons.png",
    name: "24/7 Customer Support",
    text: "Euismod faucibus turpis eu gravida mi. Pellentesque et velit aliquam sed faucib turpis eu gravida mi. Pellentesque et velit aliquam sed mi. ",
  },
  {
    icon: "../src/assets/icons.png",
    name: "Regular Updates",
    text: "Euismod faucibus turpis eu gravida mi. Pellentesque et velit aliquam sed faucib turpis eu gravida mi. Pellentesque et velit aliquam sed mi. ",
  },
];
</script>

<style lang="scss" scoped></style>
