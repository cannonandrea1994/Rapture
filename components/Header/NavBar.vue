<template>
  <nav class="site-nav">
    <ul class="site-nav__list">
      <li class="site-nav__item"><nuxt-link :to="'/'">Home</nuxt-link></li>
      <li class="site-nav__item"><nuxt-link :to="{ name: 'page' }">Page</nuxt-link></li>
      <li class="site-nav__item"><nuxt-link :to="{ name: 'posts' }">Posts</nuxt-link></li>
      <li class="site-nav__item">item</li>
    </ul>
  </nav>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss" scoped>
li {
  display: inline;
  margin: 35px;
  font-family: Montserrat, sans-serif;
}


.site-nav {
  padding: 66px 0px 214px 0px;
}
a {
  color: #ffffff;
}
</style>