<template>
  <div class="download-page">
    <div class="columns">
      <div class="column">
        <div class="columns">
          <div class="column"></div>
          <div class="column is-four-fifths store-content">
            <section class="hero hero-fix-size">
              <div class="container align-start">
                <h1 class="title has-text-weight-semibold">Download our App now !</h1>
                <h2
                  class="subtitle is-size-6 mt-10"
                >The rise of mobile devices transforms the way we consume. elevant channels such as Facebook.</h2>
              </div>
            </section>
            <section>
                <div class="container align-start app-store is-mobile">
                    <img src="../assets/img/download/play-store.png"/>
                    <img src="../assets/img/download/app-store-apple.png" />
                </div>
            </section>
          </div>
        </div>
      </div>
      <div class="column">
        <img src="../assets/img/download/download-object.png" />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "download-page"
};
</script>
<style scoped>
    .store-content{
        margin: 0px 10px;
    }
    .app-store{
        margin-top:30px;
    }
    .app-store img{
        margin:10px;
        width: 150px;
    } 
</style>