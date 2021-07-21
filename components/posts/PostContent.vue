<template>
  <div>
    <b-col md="3">
    <b-card
      :title=title
      :img-src=image
      img-alt="Image"
      img-top
      tag="article"
      style="max-width: 40rem"
      class="mb-2"
    >
      <b-card-text>
        {{ content }}        
      </b-card-text>

      <b-button href="#" variant="primary">Reading</b-button>
    </b-card>
    </b-col>
  </div>
</template>

<script>
export default {
  props: {
    id: {
      type: String,
      required: false
    },
    title: {
      type: String,
      required: true
    },
    content: {
      type: String,
      required: true
    },
    image: {
      type: String,
      required: true
    }
  }
}
</script>

<!--style scoped>
  b-card {
    position: left;
  }
</!--style>