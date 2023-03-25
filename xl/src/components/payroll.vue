<template>
  <div class="bg-[#000d2c] py-24">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto max-w-2xl lg:mx-0">
        <h2 class="text-3xl font-bold tracking-tight text-[#fffcc2] sm:text-4xl">Payroll</h2>
        <p class="mt-6 text-lg leading-8 font-semibold text-[#f2efd8]">Streamline your payroll process with our expert service - accurate, efficient, and always on time.</p>
      </div>
      <dl class="mx-auto mt-16 grid max-w-2xl grid-cols-1 gap-x-8 gap-y-16 text-base leading-7 sm:grid-cols-2 lg:mx-0 lg:max-w-none lg:grid-cols-2">
        <div v-for="feature in features" :key="feature.name">
          <dt class="font-semibold text-[#f2efd8]">{{ feature.name }}</dt>
          <dd class="mt-1 text-gray-300">{{ feature.description }}</dd>
        </div>
      </dl>
    </div>
  </div>
</template>

<script setup>
const features = [
  {
    name: 'Employee Setup',
    description:
        'Accurate T4s made easy - we set up your employees on our system to ensure their information is correct come tax time.',
  },
  {
    name: 'Hourly Payroll Processing',
    description:
        'Save time and hassle - email or fax us your hours and we\'ll process your payroll weekly, bi-weekly, semi-monthly, or monthly.',
  },
  {
    name: 'Cheque Writing',
    description:
        'Flexibility in payroll management - we provide payroll information and you can write the cheques at your convenience.',
  },
  {
    name: 'Record of Employment',
    description:
        'Stay compliant with ease - we provide Record of Employment forms for terminated employees.',
  },
  {
    name: 'Source Deduction Report',
    description:
        'Stay on top of your finances - we provide a monthly report of your source deductions and due dates to avoid penalties.',
  },
  {
    name: 'T4 Preparation',
    description:
        'Effortless year-end tax prep - we prepare and provide T4 forms for your employees.',
  },
]
</script>