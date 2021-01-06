<template>
  <header class="page-head" style="background-image: url('/Background.png')">
    <div class="container">
      <div class="row">
        <div class="col-md-6 offset-md-3 text-center">
          <div class="headline">
            <img src="LogoRapture.png">
          </div>
          <div class="input-container">
            <input type="text" class="input-field"/>
            <button class="input-button">I WANT MORE TRAFFIC</button>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
import Button from './Button.vue'
  export default {
    
  }
</script>

    Button
<style lang="scss" scoped>
  .page-head {
    height: 100vh;
    width: 100vw;
    display: flex;
    background-size:cover;
    background-repeat: no-repeat;
    color: #fff;
  }
  .headline {
    padding-top: 118px;
  }
  .input-container {
    display: flex;
    width: 600px;
    border: 1px solid #a9a9a9;
    justify-content: space-between;
  }
  .input-container input:focus, .input-container input:active {
    outline: none;
  }
  .input-container input {
    border: none;
  }
  .input-button {
    display: inline;
    width: 250px;
    height: 48px;
  }
  .input-field {
    background-color: transparent;
  }
</style>