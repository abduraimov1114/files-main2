<template>
  <section class="live-section">
    <div class="auto-container">
      <div class="sec-title centered">
        <h2 style="font-size:38px; !important">кадры из рабочего процесса <span class="dot">.</span></h2>
      </div>
      <div class="main-image-box">
        <div class="image-layer" style="background-image: url(/images/resource/featured-image-3.jpg);"></div>
        <div class="inner clearfix">
          <div class="round-box wow fadeInUp" data-wow-delay="0ms" data-wow-duration="1500ms">
            <div class="round-inner">
              <div class="vid-link">
                <a href="https://www.youtube.com/watch?v=Get7rqXYrbQ" class="glightbox2">
                  <div class="icon"><span class="flaticon-play-button-1"></span><i
                    class="ripple"></i></div>
                </a>
              </div>
              <div class="title">
                <h6>вы можете следить за нашим рабочим процессом в этом видео</h6> <!--<br><h3>excited about</h3>-->
              </div>
              <div class="more-link"><nuxt-link to="/about">Read More</nuxt-link></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
      name: "LiveSection",
      mounted() {
        new GLightbox({
          selector: '.glightbox2',
          touchNavigation: true,
          loop: true,
          autoplayVideos: true
        });
      }

    }
</script>

<style scoped>

</style>
