<template>
  <Swiper @swiper="onSwiper" :loop="true" class="mySwiper">
    <div>
      <button @click.stop="slider.slidePrev()">prev</button>
      <button @click.stop="slider.slideNext()">next</button>
    </div>

    <Swiper-slide>Slide 1</Swiper-slide>
    <swiper-slide>Slide 2</swiper-slide>
    <swiper-slide>Slide 3</swiper-slide>
  </Swiper>
</template>
<script setup>
import { ref } from "vue";
import "swiper/css";
import { Swiper, SwiperSlide } from "swiper/vue";

const slider = ref(null);
const onSwiper = (swiper) => {
  slider.value = swiper;
};
</script>
