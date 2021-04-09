<template>
    <div class="single-post-page">
        <section>
        <h1 class="post-title">The Tile For You</h1>
        <div class="post-details">
          <div class="post-detail">BBBBBBBBBBBBBBBBB</div>
          <div class="post-detail">WWWWWWWWWWW</div>
        </div>
        <p class="post-content">Nice To see You</p>
        </section>
        <p>  Let Me a thin this domain <a href="mailto:tariq.1994t12@gmail.com">tariq.1994t12@gmail.com</a>.</p>
        <section class="post-feedback">

        </section>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style  scoped>
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