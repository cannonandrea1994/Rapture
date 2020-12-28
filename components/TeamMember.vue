<template>
  <div class="staff">
    <div class="staff__image">
    </div>
  </div>
</template>

<script>
export default {
  props: {
    img: {
      type: String,
      default: 'staff.png'
    },
    name: {
      type: String,
      default: '',
      required: true
    },
    title: {
      type: String,
      default: ''
    }
  },
}
</script>
<style lang="scss" scoped>
</style>
