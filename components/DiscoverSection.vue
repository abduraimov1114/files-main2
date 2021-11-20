<template>
  <section class="discover-section">
    <div class="auto-container">
      <div class="sec-title centered">
        <h2>Discover the world of best <br>linoor agency <span class="dot">.</span></h2>
      </div>
      <div class="row clearfix">
        <!--Discover Block-->
        <div class="discover-block col-lg-6 col-md-12 col-sm-12">
          <div class="inner-box">
            <div class="image-box"><img src="/images/resource/featured-image-11.jpg" alt=""></div>
            <div class="cap-box wow fadeInUp" data-wow-delay="0ms" data-wow-duration="1500ms">
              <div class="cap-inner">
                <h5>All-in-One Web Solution for Your Business</h5>
                <div class="more-link"><nuxt-link to="/about"><span
                  class="fa fa-angle-right"></span></nuxt-link></div>
              </div>
            </div>
          </div>
        </div>
        <!--Discover Block-->
        <div class="discover-block col-lg-6 col-md-12 col-sm-12">
          <div class="inner-box">
            <div class="image-box"><img src="/images/resource/featured-image-12.jpg" alt=""></div>
            <div class="cap-box wow fadeInUp" data-wow-delay="300ms" data-wow-duration="1500ms">
              <div class="cap-inner">
                <h5>The best digital agency you’ll ever need</h5>
                <div class="more-link"><nuxt-link class="theme-btn" to="/about"><span
                  class="fa fa-angle-right"></span></nuxt-link></div>
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
        name: "DiscoverSection"
    }
</script>

<style scoped>

</style>
