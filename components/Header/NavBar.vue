<template>
  <nav class="site-nav">
    <ul class="site-nav__list">
      <li class="site-nav__item"><nuxt-link :to="'/'">Home</nuxt-link></li>
      <li class="site-nav__item"><nuxt-link :to="{ name: 'page' }">Page</nuxt-link></li>
      <li class="site-nav__item"><nuxt-link :to="{ name: 'posts' }">Posts</nuxt-link></li>
      <li><div class="headline">
      <img src="/LogoRapture.png"></div></li>
      <li class="site-nav__item"><nuxt-link :to="{ name: 'help' }">Help</nuxt-link></li>
      <li class="sign-in"><nuxt-link :to="{ name: 'index' }">Sign In</nuxt-link></li>
      <li><button>Sign Up!</button></li>
    </ul>
  </nav>
</template>

<script>
  export default {}
</script>

<style lang="scss" scoped>
.site-nav__list {
  padding-left: 360px;
}
.headline {
  display: inline-block;
  margin: 0px 50px 0px 50px;
}
li {
  display: inline;
  margin: 35px;
  font-family: Montserrat, sans-serif;
  font-size: 16px;
}
.site-nav__item_right {
  display: inline;
  margin-left: 468.5px;
}
.sign-in {
 &:hover,
 &:focus{
  box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);
 }
}
button {
  border: .5px;
  border-radius: 20px;
  height: 100%;
  width: 100%;
  max-width: 100px;
  max-height: 36px;
  background-color: transparent;
  color: #ffffff;
  transition: all .2s ease-in-out;
&:hover,
&:focus {
  background: #3B55E6;
  color: #ffffff;
  text-decoration: none;
  box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);
 } 
}
.site-nav {
  padding: 66px 0px 214px 0px;
}
a {
  color: #ffffff;
}
</style>