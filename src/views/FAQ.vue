<template>
  <div class="faq">
    <section class="hero hero-fix-size">
      <div class="hero-body">
        <div class="container">
          <h1 class="title has-text-weight-normal">Frequently asked questions</h1>
          <div>
            <h2 class="subtitle is-size-6">
              The rise of mobile devices transforms the way we consume information entirely
              and the world's most elevant channels such as Facebook.
            </h2>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="container align-start faq-option">
        <div class="columns">
          <div class="column"></div>

          <div class="column is-three-quarters">
            <b-collapse :open="false" aria-id="faq1">
              <div class="columns faq-btn is-mobile" slot="trigger" aria-controls="faq1">
                <div class="column is-three-quarters align-start child-center">
                  <p
                    class="title is-6 has-text-weight-semibold"
                  >How to contact with riders emergency?</p>
                </div>
                <div class="column plus-icon child-center">
                  <p class="title is-3 has-text-weight-normal align-end">+</p>
                </div>
              </div>
              <div class="color-bg-shadow content mt-10">
                <p class="title is-5 is-spaced">How to contact with riders emergency?</p>
                <p class="subtitle">
                  Leverage agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition. Organically grow the holistic world view of disruptive innovation via workplace diversity and empowerment.
                  Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.
                </p>
              </div>
            </b-collapse>

            <b-collapse :open="false" aria-id="faq2">
              <div class="columns faq-btn is-mobile" slot="trigger" aria-controls="faq2">
                <div class="column is-three-quarters align-start child-center">
                  <p
                    class="title is-6 has-text-weight-semibold"
                  >App installation failed, how to update system information?</p>
                </div>
                <div class="column plus-icon child-center">
                  <p class="title is-3 has-text-weight-normal align-end">+</p>
                </div>
              </div>
              <div class="color-bg-shadow content mt-10">
                <p
                  class="title is-5 is-spaced"
                >App installation failed, how to update system information?</p>
                <p class="subtitle">
                  Leverage agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition. Organically grow the holistic world view of disruptive innovation via workplace diversity and empowerment.
                  Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.
                </p>
              </div>
            </b-collapse>
            <b-collapse :open="false" aria-id="faq3">
              <div class="columns faq-btn is-mobile" slot="trigger" aria-controls="faq3">
                <div class="column align-start is-three-quarters child-center">
                  <p
                    class="title is-6 has-text-weight-semibold"
                  >Website reponse taking time, how to improve?</p>
                </div>
                <div class="column plus-icon child-center">
                  <p class="title is-3 has-text-weight-normal align-end">+</p>
                </div>
              </div>
              <div class="color-bg-shadow content mt-10">
                <p class="title is-5 is-spaced">Website reponse taking time, how to improve?</p>
                <p class="subtitle">
                  Leverage agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition. Organically grow the holistic world view of disruptive innovation via workplace diversity and empowerment.
                  Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.
                </p>
              </div>
            </b-collapse>
            <b-collapse :open="false" aria-id="faq4">
              <div class="columns faq-btn is-mobile" slot="trigger" aria-controls="faq4">
                <div class="column align-start is-three-quarters child-center">
                  <p class="title is-6 has-text-weight-semibold">New update fixed all bug and issues</p>
                </div>
                <div class="column plus-icon child-center">
                  <p class="title is-3 has-text-weight-normal align-end">+</p>
                </div>
              </div>
              <div class="color-bg-shadow content mt-10">
                <p class="title is-5 is-spaced">New update fixed all bug and issues</p>
                <p class="subtitle">
                  Leverage agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition. Organically grow the holistic world view of disruptive innovation via workplace diversity and empowerment.
                  Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.
                </p>
              </div>
            </b-collapse>
            <b-collapse :open="false" aria-id="faq5">
              <div class="columns faq-btn is-mobile" slot="trigger" aria-controls="faq5">
                <div class="column align-start is-three-quarters child-center">
                  <p
                    class="title is-6 has-text-weight-semibold"
                  >How to contact with riders emergency?</p>
                </div>
                <div class="column plus-icon child-center">
                  <p class="title is-3 has-text-weight-normal align-end">+</p>
                </div>
              </div>
              <div class="color-bg-shadow content mt-10">
                <p class="title is-5 is-spaced">How to contact with riders emergency?</p>
                <p class="subtitle">
                  Leverage agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition. Organically grow the holistic world view of disruptive innovation via workplace diversity and empowerment.
                  Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.
                </p>
              </div>
            </b-collapse>
          </div>
          <div class="column"></div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "faq"
};
</script>
<style scoped>
.faq{
    margin: 0px 10px;
}
.hero-fix-size .title {
  max-width: unset;
}
.faq-option .faq-btn {
  text-align: start;
  background-color: #b8b9b642;
  border: none;
  border-radius: unset;
  height: 50px;
  margin: 10px 0px 0px 0px;
}
.content {
  padding: 30px;
}
.content .title {
  margin-left: 15px;
}
.content .subtitle {
  font-size: 11pt;
}
</style>