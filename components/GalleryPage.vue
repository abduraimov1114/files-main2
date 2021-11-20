<template>
  <section class="gallery-section">
    <div class="auto-container">
      <!--MixitUp Galery-->
      <div class="mixitup-gallery">
          <!--Filter-->
          <div class="filters centered clearfix">
            <ul class="filter-tabs filter-btns clearfix">
              <li class="filter mixitup-control-active" data-role="button" data-filter="all">Все<sup></sup></li>
              <li class="filter" data-role="button" data-filter=".branding">Подиум<sup></sup></li>
              <li class="filter" data-role="button" data-filter=".illustration">Акустика<sup></sup></li>
              <li class="filter" data-role="button" data-filter=".photography"> <span style="font-size:28px;">LED </span> экраны<sup></sup></li>
              <li class="filter" data-role="button" data-filter=".web-design">Праздничное освещение.<sup></sup></li>
            </ul>
        </div>
        <div class="filter-list row">
          <!-- Gallery Item -->
          <div class="gallery-item mix all web-design col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <figure class="image"><img src="/images/gallery/podium.png" alt=""></figure>
              <a href="/images/gallery/podium.png" class="lightbox-image overlay-box"
                 data-fancybox="gallery"></a>
              <div class="cap-box">
                <div class="cap-inner">
                  <div class="cat"><span>Подиум</span></div>
                  <div class="title">
                    <h5><nuxt-link to="/portfolio-single">Navoiy-hd</nuxt-link></h5>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Gallery Item -->
          <div class="gallery-item mix all photography web-design col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <figure class="image"><img src="/images/gallery/13.jpg" alt=""></figure>
              <a href="/images/gallery/13.jpg" class="lightbox-image overlay-box"
                 data-fancybox="gallery"></a>
              <div class="cap-box">
                <div class="cap-inner">
                  <div class="cat"><span>LED манитор</span></div>
                  <div class="title">
                    <h5><nuxt-link to="/portfolio-single">Navoiy-hd</nuxt-link></h5>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Gallery Item -->
          <div class="gallery-item mix all branding web-design col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <figure class="image"><img src="/images/gallery/125.jpg" alt=""></figure>
              <a href="/images/gallery/125.jpg" class="lightbox-image overlay-box"
                 data-fancybox="gallery"></a>
              <div class="cap-box">
                <div class="cap-inner">
                  <div class="cat"><span>Акусстика Калонки</span></div>
                  <div class="title">
                    <h5><nuxt-link to="/portfolio-single">Navoiy-hd</nuxt-link></h5>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Gallery Item -->
          <div class="gallery-item mix all branding illustration col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <figure class="image"><img src="/images/gallery/16.jpg" alt=""></figure>
              <a href="/images/gallery/16.jpg" class="lightbox-image overlay-box"
                 data-fancybox="gallery"></a>
              <div class="cap-box">
                <div class="cap-inner">
                  <div class="cat"><span>LED маниторы</span></div>
                  <div class="title">
                    <h5><nuxt-link to="/portfolio-single">Navoiy-hd</nuxt-link></h5>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Gallery Item -->
          <div
            class="gallery-item mix all branding illustration photography web-design col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <figure class="image"><img src="/images/gallery/led.jpg" alt=""></figure>
              <a href="/images/gallery/led.jpg" class="lightbox-image overlay-box"
                 data-fancybox="gallery"></a>
              <div class="cap-box">
                <div class="cap-inner">
                  <div class="cat"><span>LED освещение</span></div>
                  <div class="title">
                    <h5><nuxt-link to="/portfolio-single">Navoiy-hd</nuxt-link></h5>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- Gallery Item -->
          <div class="gallery-item mix all illustration photography col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <figure class="image"><img src="/images/gallery/podium.jpg" alt=""></figure>
              <a href="/images/gallery/podium.jpg" class="lightbox-image overlay-box"
                 data-fancybox="gallery"></a>
              <div class="cap-box">
                <div class="cap-inner">
                  <div class="cat"><span>Подиум</span></div>
                  <div class="title">
                    <h5><nuxt-link to="/portfolio-single">Navoiy-hd</nuxt-link></h5>
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
    name: "GalleryPage",
    data () {
      return {
        mixer: null
      }
    },
    mounted () {
      const containerEl = document.querySelector('.filter-list')
      this.mixer = new this.mixitup(containerEl, {
      });

      new GLightbox({
        selector: '.lightbox-image',
        touchNavigation: true,
        loop: true,
        autoplayVideos: true
      });
    },
  }
</script>

<style scoped>

</style>
