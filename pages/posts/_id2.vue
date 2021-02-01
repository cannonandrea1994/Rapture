<template>
  <body>
    <div class="container">
      <div id="image">
       <img src='/Background.png' alt="..." />
      <div class="section"> 
      </div>
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
#image {
height: 200px;
width: 200px;
background-image: url('/Background.png');
background-repeat: no-repeat;
opacity: 0.5;
}

body {
  height: 100%;
  max-width: 100vw;
  max-height: 100vh;
}
</style>