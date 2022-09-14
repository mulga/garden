<template>
  <section>
    <!-- <div class="container"> -->
    <div class="hero-wrapper grid">
      <div class="hero-image">
        <div class="green-area">
          <div class="green-front"></div>
          <div class="green-back"></div>
        </div>
        <img src="@/assets/pot.png" alt="" />
      </div>
      <div class="hero-text">
        <h1 class="hero-title-secondary">It’s Kids-Friendly Plants!</h1>
        <p class="hero-text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore.
        </p>
        <button class="btn btn-primary">Pre-Order Now</button>
      </div>
    </div>
    <!-- </div> -->
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.hero-image {
  position: relative;
}
.hero-image img {
  position: absolute;
  bottom: 0;
  left: 10%;
  width: 450px;
}

.green-area {
  position: relative;
}

.green-back {
  position: absolute;
  top: -60px;
  left: -150px;
  width: 631px;
  height: 465px;
  background-color: #44ab9d;
  border-top-right-radius: 50px;
  z-index: -1;
}

.green-front {
  width: 631px;
  height: 465px;
  background-color: #136b5f;
  border-top-right-radius: 50px;
}

.grid {
  /* grid-template-columns: 1fr 1fr; */
  grid-template-columns: repeat(auto-fit, minmax(220px, auto));
  gap: clamp(1rem, -0.6429rem + 10.7143vw, 9rem);
}
.hero-text {
  margin: 28px 0;
}
</style>
