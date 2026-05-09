<script setup lang="ts">
const projects = ref([
  {
    id: 1,
    title: "Shoe Store",
    description: "I have done this awesome ecommerce website in the recent time...",
    url: "/images/1.jpg",
    projectLink: ""
  },
  {
    id: 2,
    title: "OnlineShop",
    description: "I have done this awesome ecommerce website in the recent time...",
    url: "/images/2.jpg",
    projectLink: ""
  },
  {
    id: 3,
    title: "Shoe Store",
    description: "I have done this awesome ecommerce website in the recent time...",
    url: "/images/3.png",
    projectLink: ""
  },
  {
    id: 4,
    title: "Shoe Store",
    description: "I have done this awesome ecommerce website in the recent time...",
    url: "/images/4.png",
    projectLink: ""
  },
  {
    id: 5,
    title: "Shoe Store",
    description: "I have done this awesome ecommerce website in the recent time...",
    url: "/images/5.jpg",
    projectLink: ""
  },
  {
    id: 6,
    title: "Shoe Store",
    description: "I have done this awesome ecommerce website in the recent time...",
    url: "/images/6.jpg",
    projectLink: ""
  },
])
</script>

<template>
  <div class="projects mt-5">
    <div class="container">
      <div class="flex justify-between item_center mb-[5rem]">
        <h1 class="w-[60%] heading text-7xl uppercase">Take a look at my recent project</h1>
        <button
          class="transition-all ease-in border-transparent border bg-sky-500 rounded-[2rem] text-xl text-gray-100 py-4 px-16 hover:text-white hover:bg-black hover:border-black hover:border-solid hover:border flex items-center">Browse All  <Icon class="ml-1 text-3xl" name="ic:twotone-arrow-right-alt" /></button>
      </div>

      <div class="flex-wrap flex justify_between gap-8">
       <ProjectCard v-for="project in projects" :key="project.id" :project="project" :imageUrl="project.url" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.projects {
  padding: 5rem 0;
}
</style>
