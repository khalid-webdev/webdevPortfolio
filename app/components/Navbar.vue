<template>
  <div class="shadow-md  py-4">
  <div class="container flex items-center justify-between">
    <div class="logo font-bold text-2xl">Webdev</div>
    <nav>
      <ul class="flex items-center justify-center gap-4">
        <li><NuxtLink class="hover:text-sky-500 px-2 font-semibold" to="/">Home</NuxtLink></li>
        <li><NuxtLink class="hover:text-sky-500 px-2 font-semibold" to="/about">About</NuxtLink></li>
        <li><NuxtLink class="hover:text-sky-500 px-2 font-semibold" to="/services">Services</NuxtLink></li>
        <li><NuxtLink class="hover:text-sky-500 px-2 font-semibold" to="/works">Works</NuxtLink></li>
      </ul>
    </nav>
    <button @click="navigateTo('/contact')" class="bg-black rounded-[20px] text-gray-100 py-2 px-5 hover:text-sky-600">Contact Me</button>
  </div>
</div>
</template>
