<template>
  <div class="shadow-md  py-4">
  <div class="container flex items-center justify-between">
    <div class="logo font-bold text-2xl">Khalid</div>
    <nav>
      <ul class="flex items-center justify-center gap-4">
        <li><NuxtLink class="transition-all ease-in hover:text-sky-500 px-2 font-semibold" to="/">Home</NuxtLink></li>
        <li><NuxtLink class="transition-all ease-in hover:text-sky-500 px-2 font-semibold" to="/about">About</NuxtLink></li>
        <li><NuxtLink class="transition-all ease-in hover:text-sky-500 px-2 font-semibold" to="/services">Services</NuxtLink></li>
        <li><NuxtLink class="transition-all ease-in hover:text-sky-500 px-2 font-semibold" to="/works">Works</NuxtLink></li>
      </ul>
    </nav>
    <button @click="navigateTo('/contact')" class="transition-all ease-in border-transparent border bg-black rounded-[20px] text-gray-100 py-1 px-5 hover:text-sky-500 hover:bg-transparent hover:border-black hover:border-solid hover:border">Contact Me</button>
  </div>
</div>
</template>
