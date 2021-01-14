<template>
  <body>
    <div class="section">
      <div class="borders">
        The physical environment is the place where every dimension of the brand can be experienced in its purest form. We are globally renowned for our strength in all areas of interior and architectural design, including retail, restaurant and workplace.
      </div>
        <div class="row">
        <div class="col-md-4">
        <li><nuxt-link :to="{ name: 'posts-id', params: { id: 1  }}"><img src="/citynight.png"></nuxt-link></li>Post #1
        </div>
        <div class="col-md-4">
          <li>  <nuxt-link :to="{ name: 'posts-id2', params: { id2: 2 }}"><img src="/foodtables.png"></nuxt-link></li>Post #2
        </div>
        <div class="col-md-4">
          <li><nuxt-link :to="{ name: 'posts-id', params: { id }}"><img src="/crappycomputers.png"></nuxt-link></li>Post #3
        </div>
      </div>
    </div> 
  </body>
</template>
<script>
  export default { 
  }
</script>

<style lang="scss" scoped>
li {
 list-style: none;
}
body {
  background-color: #413f3c;
}
.borders {
  color: #ffffff;
  font-size: 18px;
  font-family: Montserrat, sans-serif;
  text-align: center;
  border: transparent;
  height: 100%;
  width: 100%;
  max-width: 754px;
  max-height: 168px;
  position: absolute;
    top: 150px;
    left: 500px;
}
.row {
  color: #ffffff;
  text-align: center;
  width: 100%;
  max-width: 1920px;
  position: relative;
    top: 350px;
  display: inline-flex;
}


</style>