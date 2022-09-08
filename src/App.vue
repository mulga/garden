<template>
  <!-- <div class="container"> -->
  <the-header></the-header>
  <!-- </div> -->
  <the-hero></the-hero>
  <section-kids></section-kids>
</template>

<script>
import SectionKids from "./components/SectionKids.vue";
import TheHeader from "./components/TheHeader.vue";
import TheHero from "./components/TheHero.vue";
export default {
  name: "App",
  components: { TheHeader, TheHero, SectionKids },
};
</script>

<style></style>
