<template>
  <div class="bg-[#000d2c] py-24">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto max-w-2xl lg:mx-0">
        <h2 class="text-3xl font-bold tracking-tight text-[#fffcc2] sm:text-4xl">GST/PST Preparation & Filing</h2>
        <p class="mt-6 text-lg leading-8 text-[#f2efd8]">Simplify your tax compliance with our hassle-free GST/PST preparation and filing service - accurate, efficient, and always on time.</p>
      </div>
      <div class="mx-auto mt-16 max-w-2xl sm:mt-20 lg:mt-24 lg:max-w-none">
        <dl class="grid max-w-xl grid-cols-1 gap-x-8 gap-y-16 lg:max-w-none lg:grid-cols-2">
          <div v-for="feature in features" :key="feature.name" class="flex flex-col">
            <dt class="text-base font-semibold leading-7 text-[#f2efd8]">
              <div class="mb-6 flex h-10 w-10 items-center justify-center rounded-lg bg-[#1975d3]">
                <component :is="feature.icon" class="h-6 w-6 text-[#f6ecbc]" aria-hidden="true" />
              </div>
              {{ feature.name }}
            </dt>
            <dd class="mt-1 flex flex-auto flex-col text-base leading-7 text-gray-300">
              <p class="flex-auto">{{ feature.description }}</p>
            </dd>
          </div>
        </dl>
      </div>
    </div>
  </div>
</template>

<script setup>
import { CalculatorIcon, CurrencyDollarIcon } from '@heroicons/vue/24/outline'

const features = [
  {
    name: 'Automated Calculation',
    description:
        'Effortlessly stay on top of your taxes - we automatically calculate your GST and PST amounts based on monthly book recordings, providing reports and payment amounts before they\'re due.',
    icon: CalculatorIcon,
  },
  {
    name: 'Hassle-Free Payment',
    description:
        'Streamline your tax process - we provide due date reminders and offer the option to make payments on your behalf at the bank, ensuring your GST and PST payments are always on time.',
    icon: CurrencyDollarIcon,
  },
]
</script>