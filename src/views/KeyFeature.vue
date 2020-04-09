<template>
  <div class="key-feature">
    <section class="hero key-feature-hero">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">Why you should choose our app</h1>
          <div>
            <h2 class="subtitle is-size-6">
              The rise of mobile devices transforms the way we consume information entirely
              and the world's most elevant channels such as Facebook.
            </h2>
          </div>
        </div>
      </div>
    </section>
    <div class="container">
      <div class="columns is-mobile mt-20">
        <div class="column key-feature-item">
          <img src="../assets/img/key-feature/web-design.png" />
          <h2 class="has-text-weight-semibold mt-10">App Development</h2>
          <p
            class="is-size-6"
          >Get your blood tests delivered at home collact a sample from the news your blood tests.</p>
        </div>

        <div class="column key-feature-item">
          <img src="../assets/img/key-feature/trophy.png" />
          <h2 class="has-text-weight-semibold mt-10">10 Times Award</h2>
          <p
            class="is-size-6"
          >Get your blood tests delivered at home collact a sample from the news your blood tests.</p>
        </div>
        <div class="column key-feature-item">
          <img src="../assets/img/key-feature/computer.png" />
          <h2 class="has-text-weight-semibold mt-10">Cloud Storage</h2>
          <p
            class="is-size-6"
          >Get your blood tests delivered at home collact a sample from the news your blood tests.</p>
        </div>
      </div>
      <div class="columns is-mobile mt-20">
        <div class="column key-feature-item">
          <img src="../assets/img/key-feature/customer-support.png" />
          <h2 class="has-text-weight-semibold mt-10">Customization</h2>
          <p
            class="is-size-6"
          >Get your blood tests delivered at home collact a sample from the news your blood tests.</p>
        </div>

        <div class="column key-feature-item">
          <img src="../assets/img/key-feature/ui.png" />
          <h2 class="has-text-weight-semibold mt-10">UX Planning</h2>
          <p
            class="is-size-6"
          >Get your blood tests delivered at home collact a sample from the news your blood tests.</p>
        </div>
        <div class="column key-feature-item">
          <img src="../assets/img/key-feature/customer-service.png" />
          <h2 class="has-text-weight-semibold mt-10">Customer Support</h2>
          <p
            class="is-size-6"
          >Get your blood tests delivered at home collact a sample from the news your blood tests.</p>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="columns ultimate-feature">
        <div class="column">
          <section class="hero">
            <h1 class="title">Ultimate features that we built</h1>
            <h2
              class="subtitle is-size-6 mt-10"
            >The rise of mobile devices transforms the way we consume information entirely.</h2>
          </section>
          <div class="columns ultimate-feature-row is-mobile">
            <div class="column item">
              <img src="../assets/img/key-feature/web-design.png" />
              <h2 class="has-text-weight-semibold">App Development</h2>
              <p
                class="is-size-6"
              >Get your blood tests delivered at home collact a sample from the news your blood tests.</p>
            </div>
            <div class="column item">
              <img src="../assets/img/key-feature/ultimate-feature-ux.png" />
              <h2 class="has-text-weight-semibold">UX Planning</h2>
              <p
                class="is-size-6"
              >Get your blood tests delivered at home collact a sample from the news your blood tests.</p>
            </div>
          </div>
          <div class="columns ultimate-feature-row is-mobile">
            <div class="column item">
              <img src="../assets/img/key-feature/web-design.png" />
              <h2 class="has-text-weight-semibold">App Development</h2>
              <p
                class="is-size-6"
              >Get your blood tests delivered at home collact a sample from the news your blood tests.</p>
            </div>
            <div class="column item">
              <img src="../assets/img/key-feature/ultimate-feature-ux.png" />
              <h2 class="has-text-weight-semibold">UX Planning</h2>
              <p
                class="is-size-6"
              >Get your blood tests delivered at home collact a sample from the news your blood tests.</p>
            </div>
          </div>
        </div>

        <div class="column mt-20">
          <img src="../assets/img/key-feature/phone-ultimate-feature.png" />
        </div>
      </div>
      <div class="align-start">
        <button class="button-blue button is-rounded see-all">See all</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "key-feature"
};
</script>

<style scoped>
.key-feature {
  margin: 0px 10px;
}
.key-feature-hero .title {
  display: inline-block;
  max-width: 400px;
}
.key-feature-hero .subtitle {
  margin-top: 5px;
  max-width: 610px;
  display: inline-block;
}
.key-feature-item p {
  max-width: 250px;
  margin-top: 10px;
  display: inline-block;
}

.ultimate-feature {
  text-align: start;
  margin-top: 100px;
}
.ultimate-feature .title {
  display: inline-block;
  max-width: 300px;
}
.ultimate-feature .subtitle {
  margin-top: 5px;
  max-width: 400px;
  display: inline-block;
}
.ultimate-feature-row {
  margin: 30px 10px;
}
.see-all {
  margin-left: 30px;
}
</style>