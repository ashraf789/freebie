<template>
  <div class="home" id="#home">
    <div class="container main is-fluid">
      <div class="columns">
        <div class="column"></div>
        <div class="column is-half-tablet is-one-quarter-fullhd body-left">
          <div class="container">
            <div>
              <h2
                class="editor-choise subtitle img-fit is-6 is-size-7-mobile has-text-weight-medium"
              >#1 Editors Choise App of 2020</h2>
              <h1
                class="title is-size-1 is-size-2-mobile is-marginless"
              >Best app for your mordern lifestyle</h1>
              <p
                style="font-size:medium; margin:15px 0px"
              >Increment productivity with a simple to-do app. app for managing your personal budgets.</p>
            </div>
            <div>
              <button class="button-blue button is-rounded">Try for free</button>
              <button
                class="button no-border has-text-weight-medium"
                style="color:blue; margin-top:5px"
              >Watch demo video</button>
            </div>
          </div>
        </div>
        <div class="column is-one-quarter">
          <img src="../assets/img/header/mobile-screen.png" />
        </div>
        <div class="column"></div>
      </div>
    </div>
    <div class="container" style="margin-top:100px">
      <h2>Trusted by companies like</h2>
      <div class="company">
        <img src="../assets/img/supported/southwest.png" />
        <img src="../assets/img/supported/anubis.png" />
        <img src="../assets/img/supported/alonzo.png" />
        <img src="../assets/img/supported/express.png" />
        <img src="../assets/img/supported/maniac.png" />
      </div>
    </div>
    <div class="page-space"></div>
  </div>
</template>

<script>
export default {
  name: "home",
};
</script>

<style scoped>
.columns {
  margin: 0px 10px;
}
.main {
  background-image: url("../assets/img/header/header-bg.png");
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
.img-fit {
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
.editor-choise {
  background-image: url("../assets/img/header/editor-choise.png");
  padding: 4px 40px;
  width: fit-content;
}
.body-left {
  align-content: center;
  display: grid;
}
.body-left .container {
  text-align: initial;
}
.button-blue {
  width: 130px;
}

.company img {
  margin: 20px;
}
</style>