<template>
  <body>
    <div class="section">
      <div class="archive_head">
        <span class="border">The physical environment is the place where every dimension of the brand can be experienced in its purest form. We are globally renowned for our strength in all areas of interior and architectural design, including retail, restaurant and workplace.</span>
      </div>
      <div class="row">
        <div class="col-lg-4">
        <li><nuxt-link :to="{ name: 'posts-id', params: { id: (1) }}">Post #1</nuxt-link></li>
        </div>
        <div class="col-lg-4">
          <li>  <nuxt-link :to="{ name: 'posts-id', params: { id: (2) }}">Post #2</nuxt-link></li>
        </div>
        <div class="col-lg-4">
          <li><nuxt-link :to="{ name: 'posts-id', params: { id: (3) }}">Post #3</nuxt-link></li>
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
body {
  background-color: blueviolet;
}
.archive_head {
  height: 100%;
  width: 100%;
  max-width: 754px;
  max-height: 84px;
  border: 1px white solid;
  padding: 198px 419px 0px 427px;
}
</style>