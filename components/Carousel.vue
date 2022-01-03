<template>
  <div>
    <b-carousel
      id="carousel-1"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333"
    >
      <!-- Slides with custom text -->
      <nuxt-link to="/news/1">
        <b-carousel-slide img-src="https://picsum.photos/1024/480/?image=54">
          <h1 class="news-title">Hello world!</h1>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quasi,
            vero!
          </p>
        </b-carousel-slide>
      </nuxt-link>
      <b-carousel-slide img-src="https://picsum.photos/1024/480/?image=54">
        <h1 class="news-title">Hello world!</h1>
      </b-carousel-slide>
    </b-carousel>
  </div>
</template>

<style scoped>
.news-title {
  font-size: 1.4rem;
  font-weight: bold;
}
</style>
