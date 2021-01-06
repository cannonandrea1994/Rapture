<template>
  <div>
    <Header />
    <main class="main" role="main">
      <Nuxt />
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header/index';
import Footer from '@/components/Footer/index';
export default {
  components: {
    Header,
    Footer
  }
}
</script>
<style>
body {
  min-height: 6000px;
}

.nuxt-link-exact-active {
  color: red;
}

</style>
