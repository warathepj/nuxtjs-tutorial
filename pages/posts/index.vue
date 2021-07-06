<template>
  <b-container fluid>
    <Header />
    <b-container>
      <b-row class="py-5">
        <PostContent title="travel elephant home" content="lorem ipsum"/>
        <PostContent />
        <PostContent />
      </b-row>
    </b-container>
  
  </b-container>
</template>

<script>
import Header from '@/components/posts/Header.vue'
import PostContent from '@/components/posts/PostContent.vue'
export default {
  layout: 'coreLayout',
  components: {
    Header,
    PostContent,
  },
}
</script>

<style>
</style>