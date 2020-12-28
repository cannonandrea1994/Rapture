<template>
  <div class="Website">
    <div class="CTA">
      <h1>Ready to Start a Business Using a Website?</h1>
      </div>
      <div class="CTAbox">
        <span class="placement"><a href="" class="button" :class="{ 'button--full': full }">Get Started!</a></span>
      </div>
  </div>
</template>

<script>
export default {
  props: {
    full: {
      type: String
    },
  },
}
</script>

<style lang="scss" scoped>
.Website {
  background-color: #F9F9F9;
  height: 100%;
  width: 100%;
  max-height: 542px;
  max-width: 1440px;
  padding-top: 120px;
}
.h1 {
  font-weight: extrabold;
  font-family: Mulish, sans-serif;
} 
.CTA {
  font-size: 48px;
  text-align: center;
}
.CTAbox {
  margin: 48px  325px 120px 325px;
  background-color: #ffffff;
  height: 100px;
  width: 790px;
  border: solid .5px #AAAAAA;
}
$accent: #FFA149;
.button {
  color: $accent;
  outline: none;
  box-shadow: none;
  background-color: transparent;
  border: 2px solid $accent;
  font-size: 16px;
  line-height: 1;
  text-transform: uppercase;
  width: 100%;
  height: 100%;
  max-width: 200px;
  max-height: 60px;
  transition: all .2s ease-in-out;
  text-decoration: none;
  display: block;
  text-align: center;
  padding: 20px 10px;
  position: relative;
  top: 20px;
  left: 570px;
  


  &--full {
    width: 100%;
    max-width: 100%;
  }

  &:hover,
  &:focus {
    color: #ffffff;
    text-decoration: none;
  }
}
</style>