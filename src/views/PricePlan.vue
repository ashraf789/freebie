<template>
  <div id="plan">
    <div class="container">
      <section class="hero hero-fix-size">
        <div class="hero-body">
          <div class="container">
            <h1 class="title">Get awesome features, without extra charges</h1>
            <div>
              <h2 class="subtitle is-size-6">
                The rise of mobile devices transforms the way we consume information entirely
                and the world's most elevant channels such as Facebook.
              </h2>
            </div>
          </div>
        </div>
      </section>
      <div class="plan-change">
        <div class="buttons">
          <button class="button-blue button is-rounded">Monthly</button>
          <button class="button is-rounded">Annually</button>
        </div>
      </div>
      <div class="columns mt-20">
        <div class="column"></div>
        <div class="column">
          <div class="plan-monthly">
          <div class="plan-option-top child-center">
            <div>
              <span class="is-size-2 has-text-bold">
                <b>$0</b>
              </span>
              <span class="color-whight-dark">/ month</span>
            </div>
            <div class="mt-5">
              <h3 class="is-size-6 has-text-weight-semibold">Business Class</h3>
              <span class="color-whight-dark">For small teams or office</span>
            </div>
          </div>
          <div class="plan-option-bottom child-center">
            <div>
              <ul class="color-whight-dark">
                <li>Drag & Drop Builder</li>
                <li>1,000's of Templates</li>
                <li>Blog Support Tools</li>
                <li>eCommerce Store</li>
              </ul>
            </div>
            <div>
              <button class="button-blue button is-rounded">Start free trail</button>
            </div>
          </div>
          </div>
        </div>
        <div class="column">
          <div class="plan-annually">
          <div class="plan-option-top child-center">
            <div>
              <span class="is-size-2 has-text-bold">
                <b>$99</b>
              </span>
              <span class="color-whight-dark">/ month</span>
            </div>
            <div class="mt-5">
              <h3 class="is-size-6 has-text-weight-semibold">Pro Master</h3>
              <span class="color-whight-dark">For best opportunities</span>
            </div>
          </div>
          <div class="plan-option-bottom child-center">
            <div>
              <ul class="color-whight-dark">
                <li>Drag & Drop Builder</li>
                <li>1,000's of Templates</li>
                <li>Blog Support Tools</li>
                <li>eCommerce Store</li>
              </ul>
            </div>
            <div>
              <button class="button-blue button is-rounded">Subscribe Now</button>
              <button class="button is-rounded start-trial mt-10 has-text-weight-semibold">Or Start 14 days trail</button>
            </div>
          </div>
          </div>
        </div>
        <div class="column"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "price-plan"
};
</script>

<style scoped>
#plan {
  margin-top: 80px;
}

.hero-fix-size .title {
  display: inline-block;
  max-width: 500px;
}
.plan-change {
  display: flex;
  justify-content: center;
}
.plan-change div {
  border: 1px solid;
  border-color: #ebebeb;
  border-radius: 19999999px;
  width: fit-content;
  padding: 2px;
}
.plan-change div button {
  margin-bottom: 0px;
  border: none;
}
.button-blue {
  height: auto !important;
  width: auto;
}
.plan-monthly {
  padding: 0px;
  margin: 10px;
  height: 400px;
  width: 250px;
  display: inline-block;
  box-shadow: 0px 80px 30px 0px #b8b9b642;
}
.plan-annually {
  padding: 0px;
  margin: 10px;
  height: 440px;
  width: 250px;
  display: inline-block;
  border: 2px solid #ebebeb;
}
.plan-option-top {
  height: 40%;
  background-color: #fafbfc;
}
.plan-option-bottom {
  height: 60%;
}
.plan-option-bottom div li {
  margin: 10px;
  font-size: 11pt;
}
.plan-option-bottom .button-blue {
  padding-left: 30px;
  padding-right: 30px;
}
.start-trial{
    border:none; 
    color:blue
}

.plan-annually .plan-option-top {
  height: 37%;
}
.plan-annually .plan-option-bottom {
  height: 63%;
}

</style>