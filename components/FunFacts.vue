<template>
  <section class="facts-section alternate" v-observe-visibility="onVisibilityChange">
    <div class="auto-container">
      <div class="inner-container">

        <!-- Fact Counter -->
        <div class="fact-counter">
          <div class="row clearfix">

            <!--Column-->
            <div class="column counter-column col-lg-3 col-md-6 col-sm-12">
              <div class="inner">
                <div class="content">
                  <div class="count-outer count-box">
                    <span class="count-text"><countTo :startVal='0' :endVal='startCounter ? 8705 : 0' :duration='3000'></countTo></span>
                  </div>
                  <div class="counter-title">Projects Completed</div>
                </div>
              </div>
            </div>

            <!--Column-->
            <div class="column counter-column col-lg-3 col-md-6 col-sm-12">
              <div class="inner">
                <div class="content">
                  <div class="count-outer count-box alternate">
                    <span class="count-text"><countTo :startVal='0' :endVal='startCounter ? 480 : 0' :duration='3000'></countTo></span>
                  </div>
                  <div class="counter-title">Active clients</div>
                </div>
              </div>
            </div>

            <!--Column-->
            <div class="column counter-column col-lg-3 col-md-6 col-sm-12">
              <div class="inner">
                <div class="content">
                  <div class="count-outer count-box">
                    <span class="count-text"><countTo :startVal='0' :endVal='startCounter ? 626 : 0' :duration='3000'></countTo></span>
                  </div>
                  <div class="counter-title">cups of coffee</div>
                </div>
              </div>
            </div>

            <!--Column-->
            <div class="column counter-column col-lg-3 col-md-6 col-sm-12">
              <div class="inner">
                <div class="content">
                  <div class="count-outer count-box">
                    <span class="count-text"><countTo :startVal='0' :endVal='startCounter ? 9704 : 0' :duration='3000'></countTo></span>
                  </div>
                  <div class="counter-title">happy clients</div>
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
  import countTo from 'vue-count-to';
  import { ObserveVisibility } from 'vue-observe-visibility'
    export default {
      name: "FunFacts",
      components: { countTo },
      directives: {
        ObserveVisibility
      },
      data() {
        return{
          startCounter: false
        }
      },
      methods: {
        onVisibilityChange (isVisible) {
          if (isVisible){
            this.startCounter = true;
          }

        },
      }
    }
</script>

<style scoped>

</style>
