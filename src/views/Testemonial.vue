<template>
  <div id="testemonial">
    <div class="columns">
      <div class="column">
        <img src="../assets/img/testemonial/satisfaction-client.png" />
      </div>
      <div class="column col-right">
        <div class="container align-start">
          <section class="hero hero-fix-size">
            <h1 class="title has-text-weight-semibold">Meet Client Satisfaction by using product</h1>
            <h2
              class="subtitle is-size-6 mt-10"
            >The rise of mobile devices transforms the way we consume. elevant channels such as Facebook.</h2>
          </section>
          <div class="mt-20 has-text-warning">
            <span class="icon">
              <i class="fas fa-star"></i>
            </span>
            <span class="icon">
              <i class="fas fa-star"></i>
            </span>
            <span class="icon">
              <i class="fas fa-star"></i>
            </span>
            <span class="icon">
              <i class="fas fa-star"></i>
            </span>
            <span class="icon">
              <i class="fas fa-star"></i>
            </span>
          </div>
          <div class="mt-10">
            <p class="title is-6 is-spaced">User friendly & Customizable</p>
            <p class="paragraph">
              Bring to the table win-win survival strategies to ensure proactive domination.
              At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.
            </p>
          </div>
          <div class="columns is-mobile team">
            <div class="column  child-center">
              <img src="../assets/img/testemonial/adult-beard-boy-220453.png" />
            </div>
            <div class="column is-two-fifths child-center">
              <p class="title is-6">Zoltan Nemeth</p>
              <p class="subtitle is-6">CEO of Pixler Lab</p>
            </div>
            <div class="column child-center is-two-fifths" style="padding:0px">
              <div class="arrow">
                <div class="">
                  <img src="../assets/img/testemonial/left-arrow.png" />
                </div>
                <div class="">
                  <h1 class="has-background-grey-light"></h1>
                </div>
                <div class="">
                  <img src="../assets/img/testemonial/right-arrow.png" />
                </div> 
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "testemonial"
};
</script>

<style scoped>
#testemonial {
  margin-top: 100px;
}
.col-right {
  margin: 0px 10px;
}
.hero-fix-size .subtitle {
  max-width: 450px;
}
.fa-star {
  margin-right: 5px;
}
.paragraph {
  max-width: 610px;
}
.team {
  margin-top: 50px;
}
.arrow{
    text-align: center;
}
.arrow div{
    display: inline-block;
}
.arrow div h1{
    display: inline-block;
    margin: 5px;
    height: 20px;
    width:1px;
}
.arrow div img{
    width: 35px;
}

</style>