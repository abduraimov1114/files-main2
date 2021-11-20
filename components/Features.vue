<template>
  <section class="features-section">
    <div class="image-layer" style="background-image: url(/images/background/image-3.jpg);"></div>
    <div class="auto-container">
      <div class="content-box">
        <h2>Grow With Community & Experience Endless Possibilities <span>.</span></h2>
        <div class="features clearfix">
          <div class="feature-block">
            <div class="inner">
              <div class="icon-box"><span class="flaticon-design-tools"></span></div>
              <h6>latest <br>technology</h6>
            </div>
          </div>
          <div class="feature-block">
            <div class="inner">
              <div class="icon-box"><span class="flaticon-idea"></span></div>
              <h6>amazing <br>free support</h6>
            </div>
          </div>
          <div class="feature-block">
            <div class="inner">
              <div class="icon-box"><span class="flaticon-clock"></span></div>
              <h6>quick <br>services</h6>
            </div>
          </div>
        </div>
        <div class="link-box">
          <nuxt-link class="theme-btn btn-style-one" to="/about">
            <i class="btn-curve"></i>
            <span class="btn-title">Discover More</span>
          </nuxt-link>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "Features"
    }
</script>

<style scoped>

</style>
