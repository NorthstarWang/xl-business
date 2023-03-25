<template xmlns="http://www.w3.org/1999/html">
  <div class="relative isolate bg-[#000d2c]" id="contact">
    <div class="mx-auto max-w-7xl">
      <div class="relative px-6 pt-24 pb-20 sm:pt-32 lg:static lg:py-48 lg:px-8">
        <div class="mx-auto max-w-xl lg:max-w-full">
          <div class="absolute inset-y-0 left-0 -z-10 w-full overflow-hidden ring-1 ring-white/5 lg:w-full">
            <svg class="absolute inset-0 h-full w-full stroke-gray-700 [mask-image:radial-gradient(100%_100%_at_top_right,white,transparent)]" aria-hidden="true">
              <defs>
                <pattern id="54f88622-e7f8-4f1d-aaf9-c2f5e46dd1f2" width="200" height="200" x="100%" y="-1" patternUnits="userSpaceOnUse">
                  <path d="M130 200V.5M.5 .5H200" fill="none" />
                </pattern>
              </defs>
              <svg x="100%" y="-1" class="overflow-visible fill-gray-800/20">
                <path d="M-470.5 0h201v201h-201Z" stroke-width="0" />
              </svg>
              <rect width="100%" height="100%" stroke-width="0" fill="url(#54f88622-e7f8-4f1d-aaf9-c2f5e46dd1f2)" />
            </svg>
            <svg class="absolute top-[calc(100%-13rem)] -left-56 w-[72.1875rem] transform-gpu blur-3xl lg:top-[calc(50%-7rem)] lg:left-[max(-14rem,calc(100%-59rem))]" viewBox="0 0 1155 678" aria-hidden="true">
              <path fill="url(#0a9a5302-e517-46c6-85f0-d826aa6a313e)" fill-opacity=".2" d="M317.219 159.025 203.852 0 0 239.659l317.219-80.634 204.172 286.402c1.307-132.337 45.083-346.658 209.733-145.248C936.936 551.942 882.053 772.234 1031.02 636.67c119.18-108.452 130.68-295.338 121.53-375.224L855 379l21.173-362.054-558.954 142.079Z" />
              <defs>
                <linearGradient id="0a9a5302-e517-46c6-85f0-d826aa6a313e" x1="1155.49" x2="-78.208" y1="677.823" y2="203.355" gradientUnits="userSpaceOnUse">
                  <stop stop-color="#4F46E5" />
                  <stop offset="1" stop-color="#80CAFF" />
                </linearGradient>
              </defs>
            </svg>
          </div>
          <h2 class="text-3xl font-bold tracking-tight text-[#fffcc2]">Contact us</h2>
          <p class="mt-6 text-lg leading-8 text-[#f2efd8]">Our company operates from Monday to Friday, between the hours of 9am to 5pm. We welcome you to get in touch with us via phone or email.</p>
          <dl class="mt-10 space-y-4 text-base leading-7 text-gray-300">
            <div class="flex gap-x-4">
              <dt class="flex-none">
                <span class="sr-only">Telephone</span>
                <BuildingOffice2Icon class="h-7 w-6 text-gray-400" aria-hidden="true" />
              </dt>
              <dd>20 Royal Oak Pl NW<br/> Calgary, AB<br/> Canada T3G 0E6</dd>
            </div>
            <div class="flex gap-x-4">
              <dt class="flex-none">
                <span class="sr-only">Telephone</span>
                <PhoneIcon class="h-7 w-6 text-gray-400" aria-hidden="true" />
              </dt>
              <dd><a class="hover:text-white" href="tel:+1 (204) 898-9525">+1 (204) 898-9525</a></dd>
            </div>
            <div class="flex gap-x-4">
              <dt class="flex-none">
                <span class="sr-only">Telephone</span>
                <EnvelopeIcon class="h-7 w-6 text-gray-400" aria-hidden="true" />
              </dt>
              <dd><a class="hover:text-white" href="mailto:info@xlsmallbusinessservices.com">info@xlsmallbusinessservices.com</a></dd>
            </div>
            </dl>
          <p class="mt-6 text-lg leading-8 text-[#f2efd8]">Our team is dedicated to providing prompt and helpful responses to all your inquiries.  If you require assistance outside of our operating hours, we kindly ask that you leave us a message and we will get back to you as soon as possible.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { BuildingOffice2Icon, EnvelopeIcon, PhoneIcon } from '@heroicons/vue/24/outline'
</script>