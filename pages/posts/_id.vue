<template>
  <body>
    <div class="container">
      <div class="section">
        Single Post {{ 1 }}
        dhthbrtbtfrdb
      </div>
    </div>
  </body>
</template>

<script>
  export default {
    computed: {
      id() {
        return this.$route.params.id
      }
    }
  }
</script>

<style lang="scss" scoped>
body {
  height: 100%;
  max-width: 100vw;
  max-height: 100vh;
  background-color: blueviolet;
}
</style>