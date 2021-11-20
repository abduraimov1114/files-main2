<template>
  <section class="faqs-section">
    <div class="auto-container">
      <div class="row clearfix">
        <div class="faq-block col-lg-6 col-md-12 col-sm-12">
          <div class="accordion-container-one">
            <div class="ac">
              <h2 class="ac-q accordion__title-text" tabIndex="0">We help to create visual strategies</h2>
              <div class="ac-a accordion__content">
                <p class="accordion__content-desc">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.
                </p>
              </div>
            </div>

            <div class="ac accordion__content">
              <h2 class="ac-q accordion__title-text" tabIndex="0">Boostup your application traffic is just a step away</h2>
              <div class="ac-a">
                <p class="accordion__content-desc">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.
                </p>
              </div>
            </div>

            <div class="ac">
              <h2 class="ac-q accordion__title-text" tabIndex="0">How to update application new features</h2>
              <div class="ac-a accordion__content">
                <p class="accordion__content-desc">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.
                </p>
              </div>
            </div>
            <div class="ac">
              <h2 class="ac-q accordion__title-text" tabIndex="0">How to connect with the support to improve app experience</h2>
              <div class="ac-a accordion__content">
                <p class="accordion__content-desc">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.
                </p>
              </div>
            </div>

          </div>

        </div>
        <div class="faq-block col-lg-6 col-md-12 col-sm-12">
          <div class="accordion-container-two">
            <div class="ac">
              <h2 class="ac-q accordion__title-text" tabIndex="0">Pre and post launch mobile app marketing pitfalls to avoid</h2>
              <div class="ac-a accordion__content">
                <p class="accordion__content-desc">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.
                </p>
              </div>
            </div>

            <div class="ac accordion__content">
              <h2 class="ac-q accordion__title-text" tabIndex="0">Boostup your application traffic is just a step away</h2>
              <div class="ac-a">
                <p class="accordion__content-desc">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.
                </p>
              </div>
            </div>

            <div class="ac">
              <h2 class="ac-q accordion__title-text" tabIndex="0">How to update application new features</h2>
              <div class="ac-a accordion__content">
                <p class="accordion__content-desc">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.
                </p>
              </div>
            </div>
            <div class="ac">
              <h2 class="ac-q accordion__title-text" tabIndex="0">How to connect with the support to improve app experience</h2>
              <div class="ac-a accordion__content">
                <p class="accordion__content-desc">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.
                </p>
              </div>
            </div>

          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
      name: "FaqSection",
      mounted() {
        new Accordion('.accordion-container-one');
        new Accordion('.accordion-container-two');
      }
    }
</script>

<style scoped>
  .ac {
    margin-top: 10px;
    padding: 10px;
    background: #FFFFFF;
    box-sizing: border-box;
  }

  .ac>.ac-q {
    font: bold 15px Arial, sans-serif;
    font-size: 23px;
    color: #444;
    padding: 10px 30px 10px 10px;
    margin: 0;
    text-decoration: none;
    display: block;
    cursor: pointer;
    position: relative;
    font-weight: 400;
    font-family: Teko;
  }

  .ac.is-active .ac-q {
    color: #FFAA17 !important;
  }
  .ac>.ac-q::after {
    content: '+';
    text-align: center;
    width: 15px;
    right: 10px;
    top: 50%;
    -webkit-transform: translate(0, -50%);
    transform: translate(0, -50%);
    position: absolute
  }

  .ac>.ac-a {
    overflow: hidden;
    -webkit-transition-property: all;
    transition-property: all;
    -webkit-transition-timing-function: ease;
    transition-timing-function: ease
  }

  .ac>.ac-a p {
    font: 16px/1.5 Arial, sans-serif;
    color: #878e9c;
    margin: 0;
    padding: 10px;
    font-size: 18px;
    font-weight: 600;
  }

  .ac.js-enabled>.ac-a {
    visibility: hidden
  }

  .ac.is-active>.ac-a {
    visibility: visible
  }

  .ac.is-active>.ac-q::after {
    content: '\2013';
    color: #FFAA17;
  }
</style>
