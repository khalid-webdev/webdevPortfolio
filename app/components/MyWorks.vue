<script setup lang="ts">

</script>

<template>
  <div class="my_works">
    <div class="container">
      <h1 class="heading text-7xl uppercase text-center mb-20">My working process</h1>
      <div class="flex flex-row item_center w-full justify-between">
        <div class="w-[30%] flex flex-col gap-[6rem] process">
          <h2 class="text-4xl font-bold"><span class="text-xl mr-3">01. </span> Research</h2>
          <h2 class="text-4xl font-bold"><span class="text-xl mr-3">02. </span> Strategy</h2>
          <h2 class="text-4xl font-bold"><span class="text-xl mr-3">03. </span> Development</h2>
        </div>
        <div class="w-[10%]">
          <div class="vertical"></div>
          <div class="vertical"></div>
        </div>
        <div class="basis-[40%] flex flex-col gap-[3rem]">
          <h3>I start learning and researching based on client brief and resource to gain about the needs, goals,
            products and requirements to do well.</h3>
          <h3>Then start to plan and structure the project process and budget based on the discovery phase before start
            the development.</h3>
          <h3>After I completed all the processes, goals and scope, I started to do the development process such as
            creating basic codes and programming.</h3>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.my_works {
  padding: 7rem 0;
  background: #0b0b0b;
  color: whitesmoke;
}
.vertical {
  position: relative;
  border-right: 5px solid rgb(193, 193, 193);
  height: 150px;
  text-align: start;
}
.vertical:first-child{
  border-right: 5px solid oklch(68.5% 0.169 237.323);
}
.vertical:first-child::after{
  content: "";
  background: unset;
}
.vertical::before{
  content:"";
  position: absolute;
  top: -5px;
  right: -10px;
  width: 15px;
  height: 15px;
  border-radius: 50%;
  background: oklch(68.5% 0.169 237.323);
}
.vertical::after{
  content:"";
  position: absolute;
  bottom: -5px;
  right: -10px;
  width: 15px;
  height: 15px;
  border-radius: 50%;
  background: oklch(90.06% 0.0001 271.152);
}
.process h2:hover{
color: oklch(68.5% 0.169 237.323);
}
.process h2:hover .vertical{
  border-color: oklch(68.5% 0.169 237.323);
  height: 600px;
}
</style>
