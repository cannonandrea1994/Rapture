<template>
  <div class="staff">
    <div class="staff__image">
      <img :src="img" :alt="name" />
    </div>
    <div class="staff__content" v-if="name">
      <span class="staff__name">{{ name }}</span>
      <span class="staff__title">{{ title }}</span>
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
/**
 * 1. Default span is inline-block. We need it to be block in order for the items to stack.
 * 2. Look up css flexbox.
 * 3. Pushes the box back to the center properly.
 */
.staff {
  position: relative;
  width: 100%;
  margin-bottom: 100px;


  &__image {
    position: relative;
    z-index: 0;
  }

  &__content {
    width: 87%;
    background: #ffffff;
    border: 1px solid #DDDDDD;
    height: 100px;
    position: absolute;
    bottom: -50px;
    left: 50%; /** [3] */
    transform: translateX(-50%); /** [3] */
    z-index: 1;
    display: flex; /** 2 */
    justify-content: center; /** 2 */
    align-items: center; /** 2 */
    flex-direction: column; /** 2 */
  }

  span {
    display: block; /** [1] */
  }

  &__name {
    color: #333333;
    font-family: Mulish, sans-serif;
    font-weight: 700;
    font-size: 20px;
    line-height: 170%;
    margin-bottom: 2px;
  }

  &__title {
    font-family: Mulish, sans-serif;
    font-weight: 400;
    font-size: 14px;
    line-height: 170%;
  }
}
</style>
