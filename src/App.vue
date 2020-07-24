<template>
  <!-- <h1 class="text-3xl text-red-900">Hallo World</h1> -->
  <NavBar/>
  <Header id="header" class="bg-gray-900" />
  <AboutMe id="aboutme" />
  <Leistungen id="leistungen" />
  <Portfolio id="portfolio" />
  <Footer />
</template>

<script>
import NavBar from "./components/NavBar.vue";
import AboutMe from "./components/AboutMePage.vue";
import Header from "./components/Header.vue";
import Leistungen from "./components/Leistungen2.vue";
import Portfolio from "./components/Portfolio.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: { NavBar, Header, Leistungen, Portfolio, Footer, AboutMe }
};
</script>
