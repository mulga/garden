<template>
  <section>
    <div class="container">
      <div class="hero-wrapper grid">
        <div class="hero-image">
          <img src="@/assets/image2.jpeg" alt="" />
        </div>
        <div class="hero-text">
          <h1 class="hero-title-secondary">It’s Kids-Friendly Plants!</h1>
          <p class="hero-text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore.
          </p>
          <button class="btn btn-primary">Learn More</button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
section {
  padding: 10rem 0;
}

.grid {
  /* grid-template-columns: 1fr 1fr; */
  grid-template-columns: repeat(auto-fit, minmax(220px, auto));
  gap: 9rem;
}
.hero-text {
  margin: 28px 0;
}
</style>
