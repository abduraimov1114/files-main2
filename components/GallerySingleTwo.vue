<template>
  <div>
    <section class="project-single style-two">
      <div class="auto-container">
        <figure class="image-box">
          <a href="/images/resource/featured-image-20.jpg" class="portfolio" data-fancybox="gallery"><img src="/images/resource/featured-image-20.jpg" alt=""></a>
        </figure>
        <div class="text-content">
          <div class="row clearfix">
            <!-- Text COl -->
            <div class="text-col col-lg-8 col-md-12 col-sm-12">
              <div class="inner">
                <p>Все услуги оказываются «под ключ»: от разработки проекта подиума, аренды каркаса, изготовления обшивки, до его доставки и монтажа на площадке, а также брендирования, оформления ковролином, пластиковыми материалами, организации подсветки - мы готовы поставить фон-задник и любые баннерные конструкции. Производство в Москве, прокат, доставка и монтаж по любому адресу Москвы и Московской области, а также в соседние регионы. </p>
                <p>Нередко помещение в котором планируется проведение того или иного мероприятия не имеет подиум-сцены необходимого размера. Идеальным решением в данном случае является аренда профессиональной, мобильной, переносной подиум сцены. Наша подиум сцена может быть собрана любого размера и формы в самые короткие сроки как на открытых площадках так и в закрытых помещениях.
                </p>
              </div>
            </div>
            <!-- Text COl -->
            <div class="text-col col-lg-4 col-md-12 col-sm-12">
              <div class="inner">
                  <ul class="info">
                    <li><strong>Админ:</strong> <br>Jessica Brown</li>
                    <li><strong>КОЛЛ-ЦЕНТР:</strong> <br>+998(91) 339 99 99</li>
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
          <h2>Образец<span class="dot">.</span></h2>
        </div>
        <div class="row clearfix">
          <!-- Gallery Item -->
          <div class="gallery-item col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <figure class="image"><img src="/images/gallery/4.jpg" alt=""></figure>
              <a href="/images/gallery/4.jpg" class="portfolio-gallery overlay-box" data-fancybox="gallery"></a>
              <div class="cap-box">
                <div class="cap-inner">
                  <div class="cat"><span>NAVOIY-HD</span></div>
                  <div class="title">
                    <h5><a href="/portfolio-single">Аренда подиума</a></h5>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Gallery Item -->
          <div class="gallery-item col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <figure class="image"><img src="/images/gallery/5.jpg" alt=""></figure>
              <a href="/images/gallery/5.jpg" class="portfolio-gallery overlay-box" data-fancybox="gallery"></a>
              <div class="cap-box">
                <div class="cap-inner">
                  <div class="cat"><span>NAVOIY-HD</span></div>
                  <div class="title">
                    <h5><a href="/portfolio-single">Аренда подиума</a></h5>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Gallery Item -->
          <div class="gallery-item col-lg-4 col-md-6 col-sm-12">
            <div class="inner-box">
              <figure class="image"><img src="/images/gallery/6.jpg" alt=""></figure>
              <a href="/images/gallery/6.jpg" class="portfolio-gallery overlay-box" data-fancybox="gallery"></a>
              <div class="cap-box">
                <div class="cap-inner">
                  <div class="cat"><span>NAVOIY-HD</span></div>
                  <div class="title">
                    <h5><a href="/portfolio-single">Аренда подиума</a></h5>
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
    name: "GallerySingleTwo",
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
