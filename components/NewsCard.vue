<template>
  <b-card
    :title="news.title"
    img-src="https://picsum.photos/600/300/?image=25"
    img-alt="Image"
    img-top
    tag="article"
    class="mb-4 news-card"
  >
    <b-card-text>
      {{ news.details }}
    </b-card-text>

    <b-button href="#" variant="primary">Go somewhere</b-button>
  </b-card>
</template>

<script>
export default {
  props: {
    news: {
      type: [Object],
      required: true,
    },
  },
}
</script>

<style>
.news-card {
  border-radius: 15px;
  background: #eee;
}
</style>
