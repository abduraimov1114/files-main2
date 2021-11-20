<template>
  <section class="we-do-section">
    <div class="auto-container">
      <div class="row clearfix">
        <!--Left Column-->
        <div class="left-col col-lg-6 col-md-12 col-sm-12">
          <div class="inner">
            <div class="sec-title">
              <h4 style="color:#FF0000;">LED-панели или модули - это составные сегменты<span class="dot">.</span></h4>
            </div>
            <div class="featured-block clearfix">
              <div class="image"><img src="/images/resource/11.jpg" alt=""></div>
              <div class="text">из которых собирается светодиодный экран. Все светодиодные экраны производятся в виде стандартных модулей, из которых потом собирается экран нужного размера. Габариты модулей отличаются в зависимости от производителя и типа экрана..</div>
            </div>
            <div class="progress-box">
              <div class="bar-title">Digital marketing</div>
              <div class="bar">
                <div class="progress-bar">
                  <span class="progress-bar-fill" style="width: 70%;"></span>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!--Right Column-->
        <div class="right-col col-lg-6 col-md-12 col-sm-12">
          <div class="inner">
            <div class="faq-box">
              <div class="accordion-container-one">
                <div class="ac">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">We help to create visual strategies</h2>
                  <div class="ac-a accordion__content">
                    <p class="accordion__content-desc">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.</p>
                  </div>
                </div>
                <div class="ac">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">Motion Graphics & Animations</h2>
                  <div class="ac-a accordion__content">
                    <p class="accordion__content-desc">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.</p>
                  </div>
                </div>
                <div class="ac">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">We help to achieve mutual goals</h2>
                  <div class="ac-a accordion__content">
                    <p class="accordion__content-desc">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.</p>
                  </div>
                </div>

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
      name: "WedoSection",
      mounted() {
        new Accordion('.accordion-container-one');
      }

    }
</script>

<style scoped>
  .ac {
    margin-top: 10px;
    padding: 10px;
    background: #fff;
    box-sizing: border-box;
  }

  .ac>.ac-q {
    font: bold 15px Arial, sans-serif;
    font-size: 20px;
    color: #444;
    padding: 10px 30px 10px 10px;
    margin: 0;
    text-decoration: none;
    display: block;
    cursor: pointer;
    position: relative;
    font-weight: 500;
    text-transform: uppercase;
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
    color: #444;
    margin: 0;
    padding: 10px
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

  .progress-bar {
    width: 100%;
    background-color: #e0e0e0;
    padding: 3px;
    border-radius: 3px;
    box-shadow: inset 0 1px 3px rgba(0, 0, 0, .2);
  }

  .progress-bar-fill {
    display: block;
    height: 7px;
    background-color: #FFAA17;
    border-radius: 3px;

    transition: width 500ms ease-in-out;
  }
</style>

