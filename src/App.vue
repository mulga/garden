<template>
  <!-- <div class="container"> -->
  <the-header></the-header>
  <!-- </div> -->
  <the-hero></the-hero>
  <section-kids></section-kids>
  <section-blog></section-blog>
  <base-testimonial>
    <section-testimonial
      v-for="item in testimonials"
      :key="item"
    ></section-testimonial>
  </base-testimonial>
  <section-pre-order> </section-pre-order>
  <section-newsletter></section-newsletter>
  <section-footer></section-footer>
</template>

<script>
import BaseTestimonial from "./components/BaseTestimonial.vue";
import SectionBlog from "./components/SectionBlog.vue";
import SectionFooter from "./components/SectionFooter.vue";
import SectionKids from "./components/SectionKids.vue";
import SectionNewsletter from "./components/SectionNewsletter.vue";
import SectionPreOrder from "./components/SectionPreOrder.vue";
import SectionTestimonial from "./components/SectionTestimonial.vue";
import TheHeader from "./components/TheHeader.vue";
import TheHero from "./components/TheHero.vue";
export default {
  name: "App",
  components: {
    TheHeader,
    TheHero,
    SectionKids,
    SectionBlog,
    SectionTestimonial,
    SectionPreOrder,
    SectionNewsletter,
    SectionFooter,
    BaseTestimonial,
  },
  inject: ["testimonials"],
};
</script>

<style></style>
