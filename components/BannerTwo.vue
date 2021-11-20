<template>
  <section class="banner-section banner-two">

    <div class="banner-carousel">
      <no-ssr>
      <carousel :items="1">
      <!-- Slide Item -->
      <div class="slide-item">
        <div class="image-layer" style="background-image: url(/images/main-slider/2.jpg);"></div>
        <div class="shape-1"></div>
        <div class="shape-2"></div>
        <div class="shape-3"></div>
        <div class="shape-4"></div>
        <div class="shape-5"></div>
        <div class="shape-6"></div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content">
              <div class="inner">
                <div class="sub-title">welcome to Linoor agency</div>
                <h1>Smart Web <br>Design Agency</h1>
                <div class="link-box">
                  <nuxt-link class="theme-btn btn-style-one" to="/about">
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
        <div class="image-layer" style="background-image: url(/images/main-slider/1.jpg);"></div>
        <div class="shape-1"></div>
        <div class="shape-2"></div>
        <div class="shape-3"></div>
        <div class="shape-4"></div>
        <div class="shape-5"></div>
        <div class="shape-6"></div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content">
              <div class="inner">
                <div class="sub-title">welcome to Linoor agency</div>
                <h1>Smart Web <br>Design Agency</h1>
                <div class="link-box">
                  <nuxt-link class="theme-btn btn-style-one" to="/about">
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
        <div class="image-layer" style="background-image: url(/images/main-slider/2.jpg);"></div>
        <div class="shape-1"></div>
        <div class="shape-2"></div>
        <div class="shape-3"></div>
        <div class="shape-4"></div>
        <div class="shape-5"></div>
        <div class="shape-6"></div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content">
              <div class="inner">
                <div class="sub-title">welcome to Linoor agency</div>
                <h1>Smart Web <br>Design Agency</h1>
                <div class="link-box">
                  <nuxt-link class="theme-btn btn-style-one" to="/about">
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
        name: "BannerTwo"
    }
</script>

<style scoped>

</style>
