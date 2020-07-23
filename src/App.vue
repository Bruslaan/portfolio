<template>
  <!-- <h1 class="text-3xl text-red-900">Hallo World</h1> -->
  <Header/>
  <Leistungen/>

</template>

<script>
import Header from "./components/Header.vue";
import Leistungen from './components/Leistungen.vue'
export default {
  name: "App",
  components: { Header, Leistungen }
};
</script>
