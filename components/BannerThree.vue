<template>
  <section class="banner-section banner-three">

    <div class="left-based-text">
      <div class="base-inner">
        <div class="hours">
          <ul class="clearfix">
            <li><span>mon - fri</span></li>
            <li><span>9am - 7pm</span></li>
          </ul>
        </div>
        <div class="social-links">
          <ul class="clearfix">
            <li><a href="#"><span>Twitter</span></a></li>
            <li><a href="#"><span>Facebook</span></a></li>
            <li><a href="#"><span>Youtube</span></a></li>
          </ul>
        </div>
      </div>
    </div>

    <div class="bg-image" style="background-image: url(/images/main-slider/banner-bg-shape-3.png);"></div>
    <div class="banner-carousel">
      <no-ssr>
      <carousel :items="1">
      <!-- Slide Item -->
      <div class="slide-item">
        <div class="round-shape-1"></div>
        <div class="round-image">
          <div class="image" style="background-image: url(/images/main-slider/image-1.jpg);"></div>
        </div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content">
              <div class="inner">
                <h1>Best Digital <br>Marketing <br>Agency</h1>
                <div class="text">We are committed to providing our customers with exceptional
                  service while offering our employees the best training.</div>
                <div class="link-box">
                  <nuxt-link class="theme-btn btn-style-two" to="/about">
                    <i class="btn-curve"></i>
                    <span class="btn-title">Discover More</span>
                  </nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Slide Item -->
      <div class="slide-item">
        <div class="round-shape-1"></div>
        <div class="round-image">
          <div class="image" style="background-image: url(/images/main-slider/image-1.jpg);"></div>
        </div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content">
              <div class="inner">
                <h1>Best Digital <br>Marketing <br>Agency</h1>
                <div class="text">We are committed to providing our customers with exceptional
                  service while offering our employees the best training.</div>
                <div class="link-box">
                  <nuxt-link class="theme-btn btn-style-two" to="/about">
                    <i class="btn-curve"></i>
                    <span class="btn-title">Discover More</span>
                  </nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Slide Item -->
      <div class="slide-item">
        <div class="round-shape-1"></div>
        <div class="round-image">
          <div class="image" style="background-image: url(/images/main-slider/image-1.jpg);"></div>
        </div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content">
              <div class="inner">
                <h1>Best Digital <br>Marketing <br>Agency</h1>
                <div class="text">We are committed to providing our customers with exceptional
                  service while offering our employees the best training.</div>
                <div class="link-box">
                  <nuxt-link class="theme-btn btn-style-two" to="/about">
                    <i class="btn-curve"></i>
                    <span class="btn-title">Discover More</span>
                  </nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      </carousel>
      </no-ssr>
    </div>
  </section>
</template>

<script>
    export default {
        name: "BannerThree"
    }
</script>

<style scoped>

</style>
