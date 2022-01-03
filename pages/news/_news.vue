<template>
  <div class="page-content">
    <div class="container">
      <div class="hero">
        <div class="imageSide">
          <img src="/images/single post banner.jpeg" alt="" />
        </div>
        <div class="titleSide">
          <h1 class="title">this is the title</h1>
          <div class="row">
            <div class="col-6">
              <p class="author">John Doe</p>
            </div>
            <div class="col-6">
              <p class="date">14 Sept, 2021</p>
            </div>
          </div>
        </div>
      </div>
      <div class="row pt-5 pb-5">
        <div class="col-md-8">
          <div class="news-content">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas
              vitae officia, incidunt, officiis aut iste laudantium dignissimos
              assumenda necessitatibus nisi voluptatibus commodi? Magni, optio.
              Nesciunt eius aperiam at recusandae asperiores mollitia ab omnis
              necessitatibus facilis sapiente maiores reprehenderit, tempora
              nulla in impedit. Magni sit obcaecati ea eligendi sapiente, quo
              aperiam cumque explicabo animi dolores, esse enim ducimus
              asperiores aliquam quaerat assumenda optio vitae. Consequatur aut
              ex obcaecati eveniet vel dignissimos iure quidem blanditiis
              facere, non quos beatae? Nisi tenetur doloribus necessitatibus
              dignissimos asperiores unde deserunt, in modi reiciendis,
              molestias alias omnis commodi. Tenetur dolore reiciendis soluta
              officiis. Cupiditate nam, placeat hic nostrum sunt unde ducimus
              eligendi labore nesciunt, explicabo modi sapiente consectetur
              dolore delectus ea minus quasi sed maiores possimus vitae
              voluptates nemo consequatur. Deleniti inventore repellat, dolorum
              nisi quod ullam veniam saepe, eos accusantium ex perferendis!
              Error odit alias numquam necessitatibus, laborum sapiente eos.
              Sunt esse cum repellat ab quia veniam in voluptatibus eos harum
              est aspernatur, laudantium a iusto iste porro enim exercitationem
              molestias et laboriosam ea debitis. Reiciendis aliquam aliquid
              fugit incidunt sint soluta ut aperiam error veritatis velit
              voluptate, nam atque tempora vitae ratione nostrum quisquam,
              provident aut! Deleniti quas sit enim, suscipit harum omnis,
              quaerat voluptatum quisquam reiciendis ipsa culpa, veniam eius
              rerum dignissimos et explicabo. Alias, enim error iure quae
              debitis, pariatur molestias dolor natus incidunt, dolore
              voluptatum ut! Magnam eum distinctio laborum voluptatum harum
              aliquam quod libero, aspernatur soluta eos, rem dicta maiores sunt
              recusandae consequatur nam error inventore ea neque saepe?
              Adipisci illum quaerat, doloremque earum atque commodi assumenda,
              aut vero illo consequatur repellat dolor ea nulla laborum! Ipsam
              corrupti similique reprehenderit natus impedit cumque obcaecati
              recusandae, ducimus, fugit corporis repudiandae possimus.
              Asperiores error nam facilis in, quos modi, sequi harum qui eius
              est animi? Beatae in dicta temporibus eius qui, a asperiores quia
              culpa eveniet, tempore aperiam, reprehenderit esse veritatis! Qui,
              cum. Magni, praesentium optio maxime dolorem facere beatae
              cupiditate voluptatem. Deserunt excepturi quo ipsam? Inventore
              provident voluptate blanditiis et enim aut fuga quas iusto,
              veritatis distinctio, nisi eos perferendis. Architecto quaerat
              animi non, officia unde neque necessitatibus odit? Dignissimos
              modi aliquam nisi aperiam, sint nemo blanditiis quaerat. Fuga ab
              totam cupiditate harum quo minus nostrum doloremque
              necessitatibus, libero perferendis tempora quasi molestiae, sint
              dolor rerum eos distinctio laudantium delectus sunt ex quas in
              consequatur! Quas minus officiis quasi architecto, facere beatae
              pariatur, reprehenderit odio amet ea repudiandae libero earum
              suscipit.
            </p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="recent-posts">
            <p>recent post card goes here</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.hero {
  height: 60vh;
  width: 100%;
  display: flex;
  column-gap: 20px;
  overflow: hidden;
}
.imageSide {
  width: 55%;
}
.imageSide img {
  width: 100%;
}
.titleSide {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
}
.title {
  text-transform: uppercase;
  font-weight: 800;
  padding-bottom: 30px;
}
.news-content {
  line-height: 1.7rem;
  letter-spacing: 1px;
  text-align: left;
  font-size: 0.9rem;
}
.author {
  color: rgb(56, 238, 11);
  font-weight: 600;
}
</style>
