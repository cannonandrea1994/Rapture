<template>
  <header class="page-head" style="background-image: url('/Background.png')">
    <div class="container">
      <div class="row">
        <div class="col-md-6 offset-md-3 text-center">
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

<style lang="scss" scoped>
  .page-head {
    height: 100vh;
    width: 100vw;
    display: flex;
    background-size:cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    color: #fff;
  }
  .input-container {
    display: flex;
    max-width: 100%;
    width: 600px;
    height: 60px;

    border: 1px solid #a9a9a9;
    border-radius: 25px;
    justify-content: space-between;
    margin-top: 631px;
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
    border-radius: 25px;
    background-color: #3B55E6;
    color: #fff;
    position: relative;
     right: 7px;
     top: 6px;
    &:hover,
    &:focus {
      box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);
    }
  }
  .input-field {
    background-color: transparent;
    color: #ffffff;
    font-size: 16px;
    font-family: Montserrat, sans-serif;
  }
</style>