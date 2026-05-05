<script setup lang="ts">

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
        <ProjectCard/>
        <ProjectCard/>
        <ProjectCard/>
        <ProjectCard/>
        <ProjectCard/>
        <ProjectCard/>
      </div>

    </div>
  </div>
</template>

<style scoped>
.projects {
  padding: 5rem 0;
}
</style>
