<template>
  <!-- <h1 class="text-3xl text-red-900">Hallo World</h1> -->
  <Header/>
  <Leistungen/>
  <Portfolio/>
</template>

<script>
import Header from "./components/Header.vue";
import Leistungen from './components/Leistungen.vue'
import Portfolio from './components/Portfolio.vue'
export default {
  name: "App",
  components: { Header, Leistungen, Portfolio }
};
</script>
