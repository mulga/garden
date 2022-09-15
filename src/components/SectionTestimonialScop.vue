<template>
  <div>
    <slot></slot>
  </div>
</template>

<script></script>

<style>
.title-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 80px;
}

.hero-title-secondary {
  max-width: 50%;
}

.testimonial-card-wrapper {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.card {
  max-width: 356px;
  padding: 52px 30px 30px 30px;
  position: relative;
  border: 0;
}

.tes-img {
  width: 53px;
  position: absolute;
  top: -25px;
  left: 21px;
}

.testimonial-text {
  font-weight: 400;
  font-size: 20px;
  line-height: 36px;
}

.testimonial-name {
  color: #136b5f;
  font-weight: 700;
  margin-top: 26px;
}
</style>
