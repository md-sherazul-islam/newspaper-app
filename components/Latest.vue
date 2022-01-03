<template>
  <div>
    <div class="container">
      <h1>The Latest</h1>
      <div class="row">
        <div v-for="news in newses" :key="news.id" class="col-md-4">
          <NewsCard :news="news" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      newses: [
        {
          id: 1,
          title: 'News Title',
          details:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
        },
        {
          id: 2,
          title: 'News Title',
          details:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
        },
        {
          id: 3,
          title: 'News Title',
          details:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
        },
        {
          id: 4,
          title: 'News Title',
          details:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
        },
        {
          id: 5,
          title: 'News Title',
          details:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
        },
        {
          id: 6,
          title: 'News Title',
          details:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
        },
        {
          id: 7,
          title: 'News Title',
          details:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
        },
        {
          id: 8,
          title: 'News Title',
          details:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
        },
      ],
    }
  },
}
</script>

<style scoped>
.card {
  border: none;
}
h1 {
  font-weight: bold;
}
.card-title {
  font-size: 1.4rem;
  font-weight: bold;
}
</style>
