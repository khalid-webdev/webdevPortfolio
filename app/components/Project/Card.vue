<script setup lang="ts">
const { project, imageUrl } = defineProps(['project', 'imageUrl'])
console.log(imageUrl);
</script>

<template>
  <div class="card flex justify-between w-[540px] p-5 bg-white border rounded-xl shadow-md">
    <div class="w-[50%]">
     <h2 class="font-semibold font-[Oswald] text-2xl">{{ project.title }}</h2>
      <p class="text-lg text-gray-600 my-4">I have done this awesome ecommerce website in the recent time...</p>
      <button class="flex transition item_center font-semibold transform hover:scale-x-[1.1] text-sky-400">More info <Icon class="ml-1 text-xl" name="ic:twotone-arrow-right-alt" /></button>
    </div>

    <div class="w-[50%]">
     <img class="w-full rounded-md h-[160px] object-cover" :src="imageUrl" alt="">
    </div>
  </div>
</template>

<style scoped>

</style>
