<template>
  <div>
    <div class="flex flex-row mt-7">
      <div class="basis-1/2 overflow-hidden ">
        <img class="w-[80%] rounded-lg" src="../assets/images/heroimage.png" alt="">
      </div>
      <div class="basis-1/2">
        <h1 class="hero_title text-7xl uppercase">Hey, I'm a Web - Developer</h1>
        <p class="text-lg my-6 text-gray-500">I'm a full-stack Web Developer based in Khulna, Bangladesh. Providing the best development services for your next projects.</p>
        <div class="flex item_center my-7">
          <button class="transition-all ease-in border-transparent border bg-sky-500 rounded-[25px] text-gray-100 py-3 px-9 hover:text-white hover:bg-black hover:border-black hover:border-solid hover:border"">About me</button>
          <div class="ml-9 flex items-center">
            <Icon class="text-6xl mr-2 text-gray-600" name="mdi:mouse-move-down"/>
            <span class="text-gray-600 text-sm">Keep scrolling</span>
          </div>
        </div>
        <div class="flex item_center gap-3">
        <h1 class="md_text text-8xl  mr-1">MD.</h1>
          <div class="flex flex-col">
            <h2 class="font-semibold text-xl font-[oswald] text-gray-700 italic">Khaleduzzaman</h2>
            <h2 class="font-semibold text-xl font-[oswald] text-gray-700 italic"> - khalid-webdev</h2>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
h1.hero_title{
    font-family: "Lilita One", sans-serif;
    word-spacing: 1.1rem;
}
h1.md_text{
      font-family: "Lilita One", sans-serif;
}

</style>
