<template>
  <div class="page-head" style="background-image: url('/Backgroundclothes.png')">
    <div>
      <button class="button">PLUG INTO RAPTURE'S PLATFORM</button>
    </div>
    <div>
      <button class="button-2">VIEW THE E-COMMERCE API</button>
    </div>
    <div class="tablet">
      <img src="/tablet.png" alt="tablet" style="width: 1472px">
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
.page-head {
  height: 100vh;
  width: 100vw;
  background-size:cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
}
.button {
  font-size: 20px;
  border: 1px solid #ffffff;
  border-radius: 25px;
  background-color: transparent;
  color: #fff;
  transition: all .2s ease-in-out;
  position: relative;
   top: 286px;
   left: 438px; 
 &:hover,
 &:focus {
  background: #3B55E6;
  color: #ffffff;
  text-decoration: none;
  box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);   
  }
}
.button-2 {
  font-size: 20px;
  border: 1px solid #ffffff;
  border-radius: 25px;
  background-color: transparent;
  color: #fff;
  transition: all .2s ease-in-out;
  position: relative;
    top: 252px;
    left: 1030px;
 &:hover,
 &:focus {
  background: #F42267;
  color: #ffffff;
  text-decoration: none;
  box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);   
  } 
}
.tablet {
  position: absolute;
    top: 443px;
    left: 240px;
}

</style>
