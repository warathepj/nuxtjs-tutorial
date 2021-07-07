<template>
    <div>
      <b-carousel id="slider"
      controls
      indicators
      >
      <div v-for="item in items">
        <b-carousel-slide
        :caption=item.caption
        :text=item.text
        :img-src=item.image
      ></b-carousel-slide>
      </div>
      
      
      </b-carousel>
    </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {caption:"A", image:require("@/assets/image/1.jpg"), text: "Nulla vitae elit libero, a pharetra augue mollis interdum."},
        {caption:"B", image:require("@/assets/image/2.jpg"), text: "Nulla vitae elit libero, a pharetra augue mollis interdum."},
        {caption:"C", image:require("@/assets/image/3.jpg"), text: "Nulla vitae elit libero, a pharetra augue mollis interdum."}

      ]
    }
  }
}
</script>

<style scoped>
  
</style>