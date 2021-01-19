<template>
  <body>
    <div class="container">
      <div class="section">
        <h3>
          We made a short movie to show you what we do here at The Rapture Startup.
        </h3>
        <div class="row">
            <div class="column left">
              <iframe  width="560" height="315" src="https://www.youtube.com/embed/bU1QPtOZQZU" frameborder="0" allow="accelerometer;     autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
              </div>
              <div class="column right">
              <iframe class="video2" width="560" height="315" src="https://www.youtube.com/embed/2iRJb15W-14" frameborder="0"      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
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
body {
  height: 100%;
  max-width: 100vw;
  max-height: 100vh;
  background-color: blueviolet;
}
h3 {
  position: absolute;
    top: 200px;
  color: #ffffff;
  text-align: center;
}
.column {
  display: inline-block;
  position: relative;
    top: 300px;
}
.left {
  width: 49%;
  text-align: center;
  position: absolute;
    left: 0px;
}
.right {
  width: 49%;
  text-align: center;
  position: absolute;
    right: 0px;
}

</style>