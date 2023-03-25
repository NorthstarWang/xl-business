<template>
  <div class="relative bg-white">
    <div class="mx-auto max-w-7xl lg:flex lg:justify-between lg:px-8 xl:justify-end">
      <div class="lg:flex lg:w-1/2 lg:shrink lg:grow-0 xl:absolute xl:inset-y-0 xl:right-1/2 xl:w-1/2">
        <div class="relative h-80 lg:-ml-8 lg:h-auto lg:w-full lg:grow xl:ml-0">
          <img class="absolute inset-0 h-full w-full bg-gray-50 object-cover" :src="YearEnd" alt="" />
        </div>
      </div>
      <div class="px-6 lg:contents">
        <div class="mx-auto max-w-2xl pt-16 pb-24 sm:pt-20 sm:pb-32 lg:mr-0 lg:ml-8 lg:w-full lg:max-w-lg lg:flex-none lg:pt-32 xl:w-1/2">
          <p class="text-base font-semibold leading-7 text-[#104b87]">Get peace of mind at tax time with</p>
          <h1 class="mt-2 text-3xl font-bold tracking-tight text-[#000d2c] sm:text-4xl">Year-end Reconciliation</h1>
          <div class="mt-10 max-w-xl text-base leading-7 text-gray-700 lg:max-w-none">
            <ul role="list" class="mt-8 space-y-6 text-[#1b2b47]">
              <li class="flex gap-x-3">
                <ScaleIcon class="mt-1 h-5 w-5 flex-none text-[#104b87]" aria-hidden="true" />
                <span>Our year-end reconciliation service begins by recording all transactions and ensuring that the general ledger is accurately maintained.</span>
              </li>
              <li class="flex gap-x-3">
                <InboxIcon class="mt-1 h-5 w-5 flex-none text-[#104b87]" aria-hidden="true" />
                <span>We reconcile all bank statements, credit cards, accounts receivable, and accounts payable to ensure that everything is in order.</span>
              </li>
              <li class="flex gap-x-3">
                <BriefcaseIcon class="mt-1 h-5 w-5 flex-none text-[#104b87]" aria-hidden="true" />
                <span>We make sure that any business expense paid for personally is recorded accurately.</span>
              </li>
              <li class="flex gap-x-3">
                <ReceiptPercentIcon class="mt-1 h-5 w-5 flex-none text-[#104b87]" aria-hidden="true" />
                <span>We prepare your corporate tax return, ensuring that all necessary deductions are claimed and that you are in compliance with all tax laws.</span>
              </li>
              <li class="flex gap-x-3">
                <WalletIcon class="mt-1 h-5 w-5 flex-none text-[#104b87]" aria-hidden="true" />
                <span>We provide you with an income statement and balance sheet for review, giving you a clear picture of your financial standing.</span>
              </li>
            </ul>
            <p class="mt-8 font-semibold text-[#000d2c]">All the invoices, bank statement, credit card statement and Cheque Stubs are scanned so if you ever audited, we don’t need to go thorough as we will be able to provide all the information to the auditor. We like to focus on your business and let us take everything related to accounting.</p>
            </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { BriefcaseIcon, ReceiptPercentIcon, InboxIcon, ScaleIcon, WalletIcon } from '@heroicons/vue/20/solid'
import YearEnd from '../assets/yearEnd.jpg'
</script>