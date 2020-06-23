<template>
  <div class="container">
    <PostResume />
  </div>
</template>

<script>
import PostResume from '~/components/PostResume.vue'
export default {
  layout: 'blog',
  components: {
    PostResume
  }
  // async asyncData ({ $axios }) {
  //   const posts = await $axios.$get('/posts')
  //   console.log(posts)
  //   return { posts }
  // }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
}
</style>
