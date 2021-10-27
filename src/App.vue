<template>
  <div id="app">
    <Nav />
    <Posts />
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Posts from './components/Posts.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Posts
  }
}
</script>

<style scoped>

</style>
