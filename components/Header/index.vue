<template>
  <header class="site-head">
    <NavBar />
  </header>
</template>

<script>
import NavBar from '@/components/Header/NavBar.vue';
  export default {
    components: {
      NavBar
    }
  }
</script>

<style lang="scss" scoped>
  .site-head {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 70px;
  }
  
</style>