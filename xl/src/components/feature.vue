<template>
  <div class="bg-[#000d2c] py-24" id="features">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto max-w-2xl lg:text-center">
        <h2 class="text-xl font-semibold leading-7 text-[#1975d3]">Our services</h2>
        <p class="mt-2 text-3xl font-bold tracking-tight text-[#fffcc2] sm:text-4xl">Everything to make you/your business stays ahead</p>
        <p class="mt-6 text-lg leading-8 text-[#f2efd8]">As a full-service accounting firm, we strive to provide our customers with a wide range of services. We handle every aspect of this important job so you're free to do what you do best: run your business effectively.</p>
      </div>
      <div class="mx-auto mt-16 max-w-2xl sm:mt-20 lg:mt-24 lg:max-w-none">
        <dl class="grid max-w-xl grid-cols-1 gap-x-8 gap-y-16 lg:max-w-none lg:grid-cols-3">
          <div v-for="feature in features" :key="feature.name" class="flex flex-col">
            <dt class="flex items-center gap-x-3 text-base font-semibold leading-7 text-[#f2efd8]">
              <component :is="feature.icon" class="h-5 w-5 flex-none text-[#1975d3]" aria-hidden="true" />
              {{ feature.name }}
            </dt>
            <dd class="mt-4 flex flex-auto flex-col text-base leading-7 text-gray-300">
              <p class="flex-auto">{{ feature.description }}</p>
            </dd>
          </div>
        </dl>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ReceiptPercentIcon, BanknotesIcon, ClipboardDocumentIcon  } from '@heroicons/vue/20/solid'

const features = [
  {
    name: 'Taxes',
    description:
        'The experienced and professional accountants at XL SBS can assist in the planning and preparation of your personal tax returns.',
    icon: ReceiptPercentIcon,
  },
  {
    name: 'Payroll',
    description:
        'XL SBS offers customized payroll services, which have the potential to save your business costs as compared to an in-house payroll professional.',
    icon: BanknotesIcon,
  },
  {
    name: 'Bookkeeping',
    description:
        'Whether you\'re a small business owner, a manager at a mid-sized corporation, or a self-employed freelancer, the team at XL SBS is at your service. Don\'t waste your valuable time on cumbersome tasks.',
    icon: ClipboardDocumentIcon,
  },
]
</script>