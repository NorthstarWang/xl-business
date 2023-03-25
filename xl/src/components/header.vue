<template>
  <div class="relative isolate overflow-hidden bg-white">
    <svg class="absolute inset-0 -z-10 h-full w-full stroke-gray-200 [mask-image:radial-gradient(100%_100%_at_top_right,white,transparent)]" aria-hidden="true">
      <defs>
        <pattern id="0787a7c5-978c-4f66-83c7-11c213f99cb7" width="200" height="200" x="50%" y="-1" patternUnits="userSpaceOnUse">
          <path d="M.5 200V.5H200" fill="none" />
        </pattern>
      </defs>
      <rect width="100%" height="100%" stroke-width="0" fill="url(#0787a7c5-978c-4f66-83c7-11c213f99cb7)" />
    </svg>
    <div class="mx-auto max-w-7xl px-6 pt-10 pb-24 sm:pb-32 lg:flex lg:py-40 lg:px-8">
      <div class="mx-auto max-w-2xl lg:mx-0 lg:max-w-xl lg:flex-shrink-0 lg:pt-8">
        <img class="h-16" :src="icon" alt="Your Company" />
        <h1 class="mt-10 text-4xl font-bold tracking-tight text-[#000d2c] sm:text-6xl">Get your taxes done the way they are meant to be.</h1>
        <p class="mt-6 text-3xl leading-8 text-[#000d2c]">Fast, accurate and professionally </p>
        <div class="mt-10 flex items-center gap-x-6">
          <a href="#"  class="rounded-md bg-[#001d5f] px-3.5 py-2.5 text-md font-semibold text-white shadow-sm hover:bg-[#002885] focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-[#002885]" @click="scrollToSection('contact')">Contact us</a>
          <a href="#"  class="text-lg font-semibold leading-6 text-[#000d2c]" @click="scrollToSection('features')">Learn more <span aria-hidden="true">→</span></a>
        </div>
      </div>
      <div class="mx-auto mt-16 flex max-w-2xl sm:mt-24 lg:ml-10 lg:mt-0 lg:mr-0 lg:max-w-none lg:flex-none xl:ml-32">
        <div class="max-w-3xl flex-none sm:max-w-5xl lg:max-w-none">
          <div class="-m-2 rounded-xl bg-gray-900/5 p-2 ring-1 ring-inset ring-gray-900/10 lg:-m-4 lg:rounded-2xl lg:p-4">
            <div class="p-4 bg-white rounded-md shadow-2xl">
              <img :src="tax" alt="App screenshot" width="1440" height="600" class="w-[60rem] rounded-md" />
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>

<script setup>
import icon from "../assets/icon.png"
import tax from "../assets/heroimage.jpg"

const scrollToSection = (id) => {
  const featuresSection = document.getElementById(id);
  const y = featuresSection.getBoundingClientRect().top + window.pageYOffset;
  window.scrollTo({ top: y, behavior: 'smooth' });
}
</script>