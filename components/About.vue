<template>
  <section class="about-section">
    <div class="auto-container">
      <div class="row clearfix">
        <!--Image Column-->
        <div class="image-column col-xl-6 col-lg-12 col-md-12 col-sm-12">
          <div class="inner">
            <div class="image-block wow fadeInLeft" data-wow-delay="0ms" data-wow-duration="1500ms"><img
              src="/images/resource/featured-image-1.jpg" alt=""></div>
            <div class="image-block wow fadeInUp" data-wow-delay="300ms" data-wow-duration="1500ms"><img
              src="/images/resource/featured-image-2.jpg" alt=""></div>
          </div>
        </div>
        <!--Text Column-->
        <div class="text-column col-xl-6 col-lg-12 col-md-12 col-sm-12">
          <div class="inner">
          
             <div class="sec-title">
              <h2>о нашей компании <br> <span style="font-size:80px; color:#FF0000;">NavoiHD</span> <span class="dot">.</span></h2>
             <!-- <div class="lower-text">РЕКЛАМА НА <span style="font-size:32px; color:black;"> LED</span>-ЭКРАНАХ.В ГОРОДЕ НАВОИ</div> --> 
            </div>
          
            <div class="text">
              <p>Компания <span style="font-size:28px; color:#FF0000;"> Navoi HD </span> является владельцем самых заметных рекламных <span style="font-size:28px; color:#FF0000;"> LED </span> Мониторов в городе НАВОИ. Компания <span style="font-size:28px; color:#FF0000;">Navoi HD</span> имеет пятилетный опыт работы в сфере <span style="font-size:28px; color:#FF0000;">LED</span> мониторов.В рекламной индустрии с каждым годом все шире применяются <span style="font-size:28px; color:#FF0000;">LED</span>-технологии, наша компания осуществляет продажу и монтаж светодиодных экранов в городе НАВОИ, а также за его пределами, предлагая рынку новые решения по мере развития отрасли светодиодной техники.</p>
            </div>
            <div class="text clearfix">
              <ul>
                <li>365 дней в году</li>
                <li>24 часа в сутки</li>
                <li>60 минут в час</li>
              </ul>
              <div class="since"><span class="txt">Since <br>2008</span></div>
            </div>
            <div class="link-box">
              <nuxt-link class="theme-btn btn-style-one" to="/about">
                <i class="btn-curve"></i>
                <span class="btn-title">в сервисе для вас</span>
              </nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "About"
    }
</script>

<style scoped>

</style>
