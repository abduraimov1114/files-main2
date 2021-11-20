<template>
  <section class="get-quote-section">
    <div class="auto-container">
      <div class="row clearfix">
        <!--Left Column-->
        <div class="left-col col-xl-8 col-lg-12 col-md-12 col-sm-12">
          <div class="inner">
            <div class="featured-block clearfix">
              <div class="image"><img src="/images/resource/featured-image-9.jpg" alt=""></div>
              <h4>our Values & Strategy</h4>
              <div class="text">Lorem Ipsum is simply proin gravida nibh vel velit auctor aliquet.
                Aenean sollicitudin, lorem is simply free text quis bibendum.</div>
            </div>
            <div class="counter">
              <div class="counter-inner clearfix">
                <div class="counter-text">
                  <div class="count-box"><span class="count-text">345600</span></div>
                  <div class="counter-title">projects was completed successfully</div>
                </div>
                <div class="counter-image"><img src="/images/resource/featured-image-10.jpg" alt="">
                </div>
              </div>
            </div>
          </div>
        </div>
        <!--Right Column-->
        <div class="right-col col-xl-4 col-lg-12 col-md-12 col-sm-12">
          <div class="inner">
            <div class="form-box wow fadeInRight" data-wow-delay="0ms" data-wow-duration="1500ms">
              <div class="default-form">
                <h4>Get a free quote <span>.</span></h4>
                <form method="post" action="#">
                  <div class="form-group">
                    <div class="field-inner">
                      <input type="text" name="username" value="" placeholder="Your Name"
                             required="">
                    </div>
                  </div>
                  <div class="form-group">
                    <div class="field-inner">
                      <input type="email" name="email" value="" placeholder="Email Address"
                             required="">
                    </div>
                  </div>
                  <div class="form-group">
                    <div class="field-inner">
                      <input type="text" name="phone" value="" placeholder="Phone Number"
                             required="">
                    </div>
                  </div>
                  <div class="form-group">
                    <div class="field-inner">
                      <select class="custom-select-box">
                        <option>Choose Service</option>
                        <option>Website Development</option>
                        <option>Graphic Designing</option>
                        <option>Digital Marketing</option>
                        <option>App Development</option>
                      </select>
                    </div>
                  </div>
                  <div class="form-group">
                    <button class="theme-btn btn-style-one">
                      <i class="btn-curve"></i>
                      <span class="btn-title">Request a quote</span>
                    </button>
                  </div>
                </form>
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
        name: "QuoteSection"
    }
</script>

<style scoped>

</style>
