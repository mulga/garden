<template>
  <section-testimonial-scop>
    <div class="container">
      <div class="title-container">
        <div class="hero-title-secondary">{{ testimonails.testText }}</div>
        <button class="btn btn-primary">See All Testimonials</button>
      </div>
      <div class="testimonial-card-wrapper">
        <div class="card" v-for="item in testimonails" :key="item">
          <img class="tes-img" src="@/assets/tes.png" alt="" />
          <div class="card-content">
            <p class="testimonial-text">{{ item.tesText }}</p>
            <p class="testimonial-name">{{ item.tesName }}</p>
          </div>
        </div>
      </div>
    </div>
  </section-testimonial-scop>
</template>

<script>
import SectionTestimonialScop from "@/components/SectionTestimonialScop.vue";
export default {
  components: { SectionTestimonialScop },
  data() {
    return {
      testimonails: [
        {
          tesText:
            "Voluptates eum officia praesentium ducimus eos molestiae rem voluptatem consectetur.",
          tesName: "Trudie",
        },
        {
          tesText:
            "Voluptates eum officia praesentium ducimus eos molestiae rem voluptatem consectetur.",
          tesName: "Nakia",
        },
        {
          tesText:
            "Voluptates eum officia praesentium ducimus eos molestiae rem voluptatem consectetur.",
          tesName: "Alf",
        },
      ],
    };
  },
  provide() {
    return {
      testimonials: this.testimonials,
    };
  },
};
</script>

<style scoped></style>
