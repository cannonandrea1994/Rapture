<template>
  <div>
    Archive 

    <ul>
      <li>
        <nuxt-link :to="{ name: 'posts-id', params: { id: 1 }}">Post #1</nuxt-link>
      </li>
      <li>
        <nuxt-link :to="{ name: 'posts-id', params: { id: 2 }}">Post #2</nuxt-link>
      </li>
      <li>
        <nuxt-link :to="{ name: 'posts-id', params: { id: 3 }}">Post #3</nuxt-link>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss" scoped>
div {
  margin-top: 200px;
}
</style>