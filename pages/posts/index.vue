<template>
  <b-container fluid>
    <Header />
    <PostList />
  
  </b-container>
</template>

<script>
import Header from '@/components/posts/Header.vue'
import PostList from '@/components/posts/PostList.vue'
export default {
  layout: 'coreLayout',
  components: {
    Header,
    PostList
  }
}
</script>

<style>
</style>