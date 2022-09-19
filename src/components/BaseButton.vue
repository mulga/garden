<template>
  <button class="btn btn-primary"><slot></slot></button>
</template>

<script>
export default {
  name: "BaseButton",
};
</script>

<style scoped>
button.btn-primary {
  background-color: var(--clr-secondary);
  border: none;
  padding: 15px 48px;
  border-radius: 33px;
  font-size: 18px;
  font-weight: 900;
  color: #27292e;
}
</style>
