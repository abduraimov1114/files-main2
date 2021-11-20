<template>
  <div class="sidebar-page-container">
    <div class="auto-container">
      <div class="row clearfix">

        <!--Content Side-->
        <div class="content-side col-lg-8 col-md-12 col-sm-12">
          <div class="service-details">
            <div class="main-image image">
              <img src="/images/resource/featured-image-16.jpg" alt="">
            </div>
            <div class="text-content">
              <h3>ПРОДАЖА <span style="font-size:56px;">LED</span> ЭКРАНЫ</h3>
              <p>Need something changed or is there something not quite working the way you envisaged?
                Is your van a little old and tired and need refreshing? Lorem Ipsum is simply dummy
                text of the printing and typesetting industry. Lorem Ipsum has been the industry's
                standard dummy text ever since the 1500s, when an unknown printer took a galley of
                type and scrambled it to make a type specimen book. It has survived not only five
                centuries, but also the leap into electronic typesetting, remaining essentially
                unchanged.</p>
              <div class="featured">
                <div class="row clearfix">
                  <div class="image-col col-md-6 col-sm-12">
                    <div class="image">
                      <img src="/images/resource/featured-image-17.jpg" alt="">
                    </div>
                  </div>
                  <div class="text-col col-md-6 col-sm-12">
                    <div class="inner">
                      <h4>planning &amp; strategy</h4>
                      <p>Lorem Ipsum is simply dummy text of the printing and typesetting
                        industry.</p>
                      <ul>
                        <li>Research beyond the business plan</li>
                        <li>Marketing options and rates</li>
                        <li>The ability to turnaround consulting</li>
                        <li>Customer engagement matters</li>
                      </ul>
                    </div>
                  </div>
                </div>
              </div>
              <p>Need something changed or is there something not quite working the way you envisaged?
                Is your van a little old and tired and need refreshing? Lorem Ipsum is simply dummy
                text of the printing and typesetting industry. Lorem Ipsum has been the industry's
                standard dummy text ever since the 1500s, when an unknown printer took a galley of
                type and scrambled it to make a type specimen book. It has survived not only five
                centuries, but also the leap into electronic typesetting, remaining essentially
                unchanged.</p>
              <p class="last">Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy text ever since the
                1500s, when an unknown printer took a galley of type and scrambled it to make a type
                specimen book. It has survived not only five centuries, but also the leap into
                electronic typesetting, remaining essentially unchanged.</p>
            </div>
          </div>
        </div>

        <!--Sidebar Side-->
        <div class="sidebar-side col-lg-4 col-md-12 col-sm-12">
          <aside class="sidebar blog-sidebar">

            <div class="sidebar-widget services">
              <div class="widget-inner">
                <div class="sidebar-title">
                  <h4>ВСЕ УСЛУГИ</h4>
                </div>
                <ul>
                  <li class="active"><a to="/web-development">ПРОДАЖА <span style="font-size:26px;">LED</span> ЭКРАНЫ</a></li>
                  <li><nuxt-link to="/БЕГУЩАЯ СТРОКА">БЕГУЩАЯ СТРОКА</nuxt-link></li>
                  <li><nuxt-link to="/аренда экрана">АРЕНДА LED ЭКРАНА</nuxt-link></li>
                  <li><nuxt-link to="/Видео стена">ВИДЕО БУКВЫ</nuxt-link></li>
                  <li><nuxt-link to="/МЕДИА ФАСАД">МЕДИА ФАСАД</nuxt-link></li>
                  <li><nuxt-link to="/Видео стена">ВИДЕО СТЕНА</nuxt-link></li>
                </ul>
              </div>
            </div>

            <div class="sidebar-widget call-up">
              <div class="widget-inner">
                <div class="sidebar-title">
                  <h4>need Linoor help?</h4>
                </div>
                <div class="text">Prefer speaking with a human to filling out a form? call corporate
                  office and we will connect you with a team member who can help.</div>
                <div class="phone"><a href="tel:666888000"><span class="icon flaticon-call"></span>666 888 000</a></div>
              </div>
            </div>


          </aside>
        </div>

      </div>
    </div>
  </div>
</template>

<script>
    export default {
        name: "ServiceDetails"
    }
</script>

<style scoped>

</style>
