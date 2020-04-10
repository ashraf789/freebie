<template>
  <div class="footer">
    <div class="container child-center">
      <div class="title is-4">
        <span class="brand-first">App</span>
        <span class="brand-second">Lab</span>
      </div>
      <div class="pages">
        <ul>
          <li>
            <a href="#">Home</a>
          </li>
          <li>
            <a href="#">Key Features</a>
          </li>
          <li>
            <a href="#">Pricing</a>
          </li>
          <li>
            <a href="#">Testemonia</a>
          </li>
          <li>
            <a href="#">FAQ</a>
          </li>
        </ul>
      </div>
      <div class="socials">
        <ul>
          <li>
            <span class="icon">
              <i class="fab fa-facebook-f"></i>
            </span>
          </li>
          <li>
            <span class="icon">
              <i class="fab fa-twitter"></i>
            </span>
          </li>
          <li>
            <span class="icon">
              <i class="fab fa-slack-hash"></i>
            </span>
          </li>
          <li>
            <span class="icon">
              <i class="fab fa-github-square"></i>
            </span>
          </li>
        </ul>
      </div>
      <div class="copiright">
          <p>
              Copyright© Syed Ashraf Ullah 2020. All rights reserved
          </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "footer"
};
</script>
<style scoped>
.footer {
    padding-top: 80px;
  background-color: #09142e;
  color: white;
}
.brand-first {
  color: #fcae61;
}
.brand-second {
  color: white;
}
.pages li {
  display: inline;
  margin: 15px;
}
.pages li a {
  color: white;
}
.socials {
  margin-top: 25px;
}
.socials li {
  display: inline;
  margin: 10px;
}
.socials li a {
  color: white;
}
.fab{
    font-size:15pt;
}

.fa-facebook-f,
.fa-twitter,
.fa-github-square {
  color: grey;
}

.copiright{
    margin-top:25px;
}
.copiright p{
    font-size: 10pt;
    color:grey;
}

/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    .footer{
        margin-top: -45px;
    }
}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
    .footer{
        margin-top: -65px;
    }
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
    .footer{
        margin-top: -53px;
    }
}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
    .footer{
        margin-top: -5%;
    }
}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
    .footer{
        margin-top: -4.2%;
    }
}
</style>