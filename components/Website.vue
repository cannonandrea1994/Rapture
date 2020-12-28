<template>
  <div class="Website">
    <div class="CTA"> </div>
  </div>
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
  &--full {
    width: 100%;
    max-width: 100%;
  }

  &:hover,
  &:focus {
    color: #ffffff;
    text-decoration: none;
  }
</style>