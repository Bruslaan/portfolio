<template>
  <!-- <h1 class="text-3xl text-red-900">Hallo World</h1> -->
  <!-- <NavBar/> -->
  <Header />
  <Leistungen />
  <Portfolio />
  <Footer />
</template>

<script>
import NavBar from "./components/NavBar.vue";
import Header from "./components/Header.vue";
import Leistungen from "./components/Leistungen.vue";
import Portfolio from "./components/Portfolio.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: { NavBar, Header, Leistungen, Portfolio, Footer }
};
</script>
