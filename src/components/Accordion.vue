<template>
  <div
    v-for="(item, index) in accordionItems"
    :key="index"
    class="accordion w-full md:w-[700px] border-b-2 border-[#C2BBFF] py-2 text-primary cursor-pointer"
  >
    <div
      class="header p-4 rounded-md text-xl md:text-2xl font-medium max-md:flex justify-between items-center"
      @click="openAccordion(index)"
    >
      <div class="max-md:flex gap-4 items-center">
        <span class="pr-4 text-[#2405F2]">{{ item.number }}</span>
        <span class="text-primary">{{ item.title }}</span>
        <span
          class="float-right opacity-70 text-4xl font-semibold duration-200"
          :class="{ 'rotate-45': isOpen[index] }"
          >+</span
        >
      </div>
    </div>
    <div
      class="body overflow-hidden duration-200"
      :class="[isOpen[index] ? 'max-h-[500px]' : 'max-h-0']"
    >
      <div class="p-4 pl-[58px] max-w-[600px]">
        {{ item.content }}
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isOpen: [],
      accordionItems: [
        {
          number: "01",
          title: "How much time does it take ?",
          content:
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.",
        },
        {
          number: "02",
          title: "What is your class naming convention ?",
          content:
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.",
        },
        {
          number: "03",
          title: "How do we communicate ?",
          content:
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.",
        },
        {
          number: "04",
          title: "I have project. Can you handle it ?",
          content:
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.",
        },
        {
          number: "05",
          title: "What is your class naming convention ?",
          content:
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.",
        },
      ],
    };
  },
  methods: {
    openAccordion(index) {
      this.isOpen[index] = !this.isOpen[index];
    },
  },
};
</script>
