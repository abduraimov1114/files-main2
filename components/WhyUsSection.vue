<template>
  <section class="why-us-section">
    <div class="auto-container">
      <div class="row clearfix">
        <!--Left Column-->
        <div class="left-col col-lg-6 col-md-12 col-sm-12">
          <div class="inner wow fadeInLeft" data-wow-delay="0ms" data-wow-duration="1500ms">
            <div class="round-box">
              <div class="image-box">
                <img src="/images/resource/featured-image-8.jpg" alt="">
              </div>
              <div class="vid-link">
                <a href="https://www.youtube.com/watch?v=Get7rqXYrbQ" class="lightbox-video">
                  <div class="icon"><span class="flaticon-play-button-1"></span><i
                    class="ripple"></i></div>
                </a>
              </div>
            </div>
          </div>
        </div>
        <!--Right Column-->
        <div class="right-col col-lg-6 col-md-12 col-sm-12">
          <div class="inner">
            <div class="sec-title">
              <h2>See Why you should choose linoor <span class="dot">.</span></h2>
            </div>
            <div class="features">
              <div class="feature">
                <div class="inner-box">
                  <h6>We think differently</h6>
                  <div class="text">Lorem Ipsum nibh vel velit auctor aliquet. Aenean sollic
                    tudin, lorem is simply free text quis bibendum.</div>
                </div>
              </div>
              <div class="feature">
                <div class="inner-box">
                  <h6>did High quality projects</h6>
                  <div class="text">Lorem Ipsum nibh vel velit auctor aliquet. Aenean sollic
                    tudin, lorem is simply free text quis bibendum.</div>
                </div>
              </div>
              <div class="feature">
                <div class="inner-box">
                  <h6>super expert team members</h6>
                  <div class="text">Lorem Ipsum nibh vel velit auctor aliquet. Aenean sollic
                    tudin, lorem is simply free text quis bibendum.</div>
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
      name: "WhyUsSection",
      mounted () {
        new GLightbox({
          selector: '.lightbox-video',
          autoplayVideos: true
        });
      },
    }
</script>

<style scoped>

</style>
