<template>
  <div class="home-page">
      <section class="intro">
       <h1>Get THe latest Tech new</h1>
      </section>
      <section class="featured-posts">
       <nuxt-link :to="'/posts/' + 1">
          <article class="post-preview">
            <div class="post-thumbnail" style="background-image: url('')"></div>
            <div class="post-content">
            <h1>Post Title</h1>
            <p>Previw Text</p>
            </div>
          </article>
       </nuxt-link>
        <nuxt-link :to="'/posts/' + 2">
          <article class="post-preview">
           <div  class="post-thumbnail"></div>
           <div   class="post-content">
           <h1>Post Title 2</h1>
           <p>Previw Text 2</p>
           </div>
          </article>
       </nuxt-link>
      </section>
  </div>
</template>

<script>
export default {
  setup () {
    

    return {}
  }
}
</script>

<style scoped>
.single-post-page {
  padding: 30px;
  text-align: center;
  box-sizing: border-box;
}

.post {
  width: 100%;
}

@media (min-width: 768px) {
  .post {
    width: 600px;
    margin: auto;
  }
}

.post-title {
  margin: 0;
}

.post-details {
  padding: 10px;
  box-sizing: border-box;
  border-bottom: 3px solid #ccc;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

@media (min-width: 768px) {
  .post-details {
    flex-direction: row;
  }
}

.post-detail {
  color: rgb(88, 88, 88);
  margin: 0 10px;
}

.post-feedback a {
  color: red;
  text-decoration: none;
}

.post-feedback a:hover,
.post-feedback a:active {
  color: salmon;
}
</style>