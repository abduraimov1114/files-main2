<template>
    <div>
      <section class="project-single">
        <div class="auto-container">
          <div class="row clearfix">
            <!-- Images COl -->
            <div class="image-col col-lg-8 col-md-12 col-sm-12">
              <div class="inner">
                <figure class="image-box">
                  <a href="/images/gallery/kalonka.jpg" class="portfolio" data-fancybox="gallery"><img src="/images/gallery/kalonka.jpg" alt=""></a>
                </figure>

                <figure class="image-box">
                  <a href="images/gallery/p15250_1.jpg" class="portfolio" data-fancybox="gallery"><img src="/images/gallery/p15250_1.jpg" alt=""></a>
                </figure>
              </div>
            </div>

            <!-- Text COl -->
            <div class="text-col col-lg-4 col-md-12 col-sm-12">
              <div class="inner">
                <div class="text-content">
                  <h5>Акустика для вас</h5>
                  <p>мы можем предоставить наши собственные акустические услуги для наших клиентов, которые любят музыку или любят громкие звуки.</p>
                  <ul class="info">
                    <li><strong>Админ:</strong> <br>Jessica Brown</li>
                    <li><strong>Call-centre:</strong> <br>+998(91) 339 99 99</li>
                    <li><strong>Рабочие часы:</strong> <br>8:00  18:00</li>
                  </ul>
                </div>
              </div>
            </div>

          </div>
        </div>
      </section>
      <!-- <div class="post-control">
        <div class="auto-container">
          <div class="inner clearfix">
            <div class="control prev"><a href="#"><span class="fa fa-angle-left"></span> &nbsp; Previous</a>
            </div>
            <div class="control next"><a href="#">Next &nbsp;<span class="fa fa-angle-right"></span></a></div>
          </div>
        </div>
      </div> -->

      <section class="gallery-section similar-gallery">
        <div class="auto-container">
          <div class="sec-title centered">
            <h2>Образцы<span class="dot">.</span></h2>
          </div>
          <div class="row clearfix">
            <!-- Gallery Item -->
            <div class="gallery-item col-lg-4 col-md-6 col-sm-12">
              <div class="inner-box">
                <figure class="image"><img src="/images/gallery/arrenda1.jpeg" alt=""></figure>
                <a href="/images/gallery/arrenda1.jpeg" class="portfolio-gallery overlay-box" data-fancybox="gallery"></a>
                <div class="cap-box">
                  <div class="cap-inner">
                    <div class="cat"><span>NAVOIY-HD</span></div>
                    <div class="title">
                      <h5><a href="/portfolio-single">Акустик Калонки</a></h5>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- Gallery Item -->
            <div class="gallery-item col-lg-4 col-md-6 col-sm-12">
              <div class="inner-box">
                <figure class="image"><img src="/images/gallery/arrenda1.jpeg" alt=""></figure>
                <a href="/images/gallery/arrenda1.jpegg" class="portfolio-gallery overlay-box" data-fancybox="gallery"></a>
                <div class="cap-box">
                  <div class="cap-inner">
                    <div class="cat"><span>NAVOIY-HD</span></div>
                    <div class="title">
                      <h5><a href="/portfolio-single">Акустик Калонки</a></h5>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- Gallery Item -->
            <div class="gallery-item col-lg-4 col-md-6 col-sm-12">
              <div class="inner-box">
                <figure class="image"><img src="/images/gallery/arrenda1.jpeg" alt=""></figure>
                <a href="/images/gallery/arrenda1.jpeg" class="portfolio-gallery overlay-box" data-fancybox="gallery"></a>
                <div class="cap-box">
                  <div class="cap-inner">
                    <div class="cat"><span>NAVOIY-HD</span></div>
                    <div class="title">
                      <h5><a href="/portfolio-single">Акустик Калонки</a></h5>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!--galeryt item-->
              <div class="gallery-item col-lg-4 col-md-6 col-sm-12">
              <div class="inner-box">
                <figure class="image"><img src="/images/gallery/arrenda1.jpeg" alt=""></figure>
                <a href="/images/gallery/arrenda1.jpeg" class="portfolio-gallery overlay-box" data-fancybox="gallery"></a>
                <div class="cap-box">
                  <div class="cap-inner">
                    <div class="cat"><span>NAVOIY-HD</span></div>
                    <div class="title">
                      <h5><a href="/portfolio-single">Акустик Калонки</a></h5>
                    </div>
                  </div>
                </div>
              </div>
            </div>
              <!--galeryt item-->
              <div class="gallery-item col-lg-4 col-md-6 col-sm-12">
              <div class="inner-box">
                <figure class="image"><img src="/images/gallery/arrenda1.jpeg" alt=""></figure>
                <a href="/images/gallery/arrenda1.jpeg" class="portfolio-gallery overlay-box" data-fancybox="gallery"></a>
                <div class="cap-box">
                  <div class="cap-inner">
                    <div class="cat"><span>NAVOIY-HD</span></div>
                    <div class="title">
                      <h5><a href="/portfolio-single">Акустик Калонки</a></h5>
                    </div>
                  </div>
                </div>
              </div>
            </div>

  <!--galeryt item-->
              <div class="gallery-item col-lg-4 col-md-6 col-sm-12">
              <div class="inner-box">
                <figure class="image"><img src="/images/gallery/arrenda1.jpeg" alt=""></figure>
                <a href="/images/gallery/arrenda1.jpeg" class="portfolio-gallery overlay-box" data-fancybox="gallery"></a>
                <div class="cap-box">
                  <div class="cap-inner">
                    <div class="cat"><span>NAVOIY-HD</span></div>
                    <div class="title">
                      <h5><a href="/portfolio-single">Акустик Калонки</a></h5>
                    </div>
                  </div>
                </div>
              </div>
            </div>



          </div>

        </div>
      </section>

    </div>
</template>

<script>
    export default {
      name: "GallerySingle",
      mounted() {
        new GLightbox({
          selector: '.portfolio',
        });
        new GLightbox({
          selector: '.portfolio-gallery',
        });
      }

    }
</script>

<style scoped>

</style>
