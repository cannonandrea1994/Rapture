<template>
  <a href="" class="button" :class="{ 'button--full': full }">Get Started</a>
</template>

<script>
export default {
  props: {
    full: {
      type: String
    },
  },
}
</script>

<style lang="scss" scoped>
$accent: #FFA149;
.button {
  outline: none;
  box-shadow: none;
  background-color: transparent;
  color: $accent;
  border: 2px solid $accent;
  font-size: 16px;
  line-height: 1;
  padding: 20px 10px;
  text-transform: uppercase;
  width: 100%;
  max-width: 200px;
  transition: all .2s ease-in-out;
  text-decoration: none;
  display: block;
  text-align: center;

  &--full {
    width: 100%;
    max-width: 100%;
  }

  &:hover,
  &:focus {
    background: $accent;
    color: #ffffff;
    text-decoration: none;
  }
}
</style>
