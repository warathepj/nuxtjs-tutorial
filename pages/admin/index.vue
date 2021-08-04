<template>
  <PostList isAdmin/>
</template>

<script>
import PostList from '@/components/posts/PostList'
export default {
  layout: "coreLayout",
  components: { PostList }
}
</script>

<style>

</style>