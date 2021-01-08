<template>
  <div class="body">
    <div class="section">
      <div class="archive_list">
        Archive 
        <ul>
          <li>
            <nuxt-link :to="{ name: 'posts-id', params: { id: (1) }}">Post #1</nuxt-link>
          </li>
          <li>
            <nuxt-link :to="{ name: 'posts-id', params: { id: (2) }}">Post #2</nuxt-link>
          </li>
          <li>
            <nuxt-link :to="{ name: 'posts-id', params: { id: (3) }}">Post #3</nuxt-link>
          </li>
        </ul>
    </div>
   </div> 
  </div>
</template>

<script>
  export default { 
  }
</script>

<style lang="scss" scoped>
.archive_list {
  margin-top: 400px;
}
.body {
  background-color: blueviolet;
}
</style>