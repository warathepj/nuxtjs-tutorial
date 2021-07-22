<template>
  <b-row class="py-5">

        <PostContent id="1" title="travel elephant home" content="lorem ipsum Lorem ipsum dolor sit, amet consectetur adipisicing elit. Asperiores eum deleniti numquam quae nemo doloremque voluptates illo ratione iste impedit voluptatum nesciunt fuga, eligendi officiis. Totam id et cum dignissimos!" image="@/assets/image/2.jpg" />
        <PostContent 
          id="2"
          title="sea travel" 
          content="lorem ipsum Lorem ipsum dolor sit, amet consectetur adipisicing elit. Asperiores eum deleniti numquam quae nemo doloremque voluptates illo ratione iste impedit voluptatum nesciunt fuga, eligendi officiis. Totam id et cum dignissimos!" 
          image="@/assets/image/1.jpg" 
        />
        
        <PostContent
          id="3"
          title="Farming" 
          content="lorem ipsum Lorem ipsum dolor sit, amet consectetur adipisicing elit. Asperiores eum deleniti numquam quae nemo doloremque voluptates illo ratione iste impedit voluptatum nesciunt fuga, eligendi officiis. Totam id et cum dignissimos!" 
          image="@/assets/image/2.jpg" 
        />

        <PostContent 
          id="4"
          title="Temple travel" 
          content="lorem ipsum Lorem ipsum dolor sit, amet consectetur adipisicing elit. Asperiores eum deleniti numquam quae nemo doloremque voluptates illo ratione iste impedit voluptatum nesciunt fuga, eligendi officiis. Totam id et cum dignissimos!" 
          image="@/assets/image/4.jpg" 
        />
      </b-row>
</template>

<script>
import PostContent from '@/components/posts/PostContent.vue';
export default {
    components: {
        PostContent
    }
}
</script>

<style>

</style>