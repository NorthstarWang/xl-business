<script setup>
import Header from "./components/header.vue";
import Footer from "./components/footer.vue";
import Feature from "./components/feature.vue"
import MR from "./components/monthReconciliation.vue"
import YR from "./components/yearReconciliation.vue"
import Contact from "./components/contact.vue"
import Payroll from "./components/payroll.vue";
import Filing from "./components/filing.vue";
</script>

<template>
  <div class="bg-white">
    <Header/>
    <Feature/>
    <payroll/>
    <filing/>
    <MR/>
    <YR/>
    <Contact/>
    <Footer/>
  </div>
</template>
