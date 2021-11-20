<template>
  <div>
  <footer class="main-footer">
    <div class="auto-container">
      <!--Widgets Section-->
      <div class="widgets-section">
        <div class="row clearfix">

          <!--Column-->
          <div class="column col-xl-3 col-lg-6 col-md-6 col-sm-12">
            <div class="footer-widget logo-widget">
              <div class="widget-content">
                <div class="logo">
                  <nuxt-link to="/"><img id="fLogo" src="/images/logoo.png" width="100" height="auto" alt="" /></nuxt-link>
              </div>  <!--
                <div class="text"><i class="fa fa-map-marker" style="color:red;"></i> Узбекситан, 210100, г. Навои, Ислам Каримов 74 A.</div>-->
                <ul class="social-links clearfix">
                  <li><a href="#"><span class="fab fa-facebook-square"></span></a></li>
                  <li><a href="#"><span class="fab fa-twitter"></span></a></li>
                  <li><a href="#"><span class="fab fa-instagram"></span></a></li>
                  <li><a href="#"><span class="fab fa-pinterest-p"></span></a></li>
                </ul>
              </div>
            </div>
          </div>

          <!--Column-->
          <!--<div class="column col-xl-3 col-lg-6 col-md-6 col-sm-12">
            <div class="footer-widget links-widget">
              <div class="widget-content">
                <h6>Explore</h6>
                <div class="row clearfix">
                  <div class="col-md-6 col-sm-12">
                    <ul>
                      <li><a href="#">About</a></li>
                      <li><a href="#">Meet Our Team</a></li>
                      <li><a href="#">Our Portfolio</a></li>
                      <li><a href="#">Latest News</a></li>
                      <li><a href="#">Contact</a></li>
                    </ul>
                  </div>
                  <div class="col-md-6 col-sm-12">
                    <ul>
                      <li><a href="#">Support</a></li>
                      <li><a href="#">Privacy Policy</a></li>
                      <li><a href="#">Terms of Use</a></li>
                      <li><a href="#">Help</a></li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>-->

          <!--Column-->
          <div style="margin-left:20%;" class="column col-xl-3 col-lg-6 col-md-6 col-sm-12">
            <div class="footer-widget info-widget">
              <div class="widget-content">
                <h6>Contact</h6>
                <ul class="contact-info">
                  <li class="address"><span class="icon flaticon-pin-1"></span> Узбекситан, 210100, г. Навои, Ислам Каримов 74 A.</li>
                  <li><span class="icon flaticon-call"></span><a href="tel:+998 (91) 339 99 99">+998 (91) 339 99 99 </a></li>
                  <li><span class="icon flaticon-call"></span><a href="tel:+998 (98) 576 99 99">+998 (98) 576 99 99 </a></li>
                  <li><span class="icon flaticon-call"></span><a href="tel:+998 (79) 210 99 99">+998 (79) 210 99 99 </a></li>
                  <li><span class="icon flaticon-email-2"></span><a
                    href="mailto:needhelp@linoor.com">info@navoi-hd.uz</a></li>
                </ul>
              </div>
            </div>
          </div>

          <!--Column-->
          <!-- <div class="column col-xl-3 col-lg-6 col-md-6 col-sm-12">
            <div class="footer-widget newsletter-widget">
              <div class="widget-content">
                <h6>Newsletter</h6>
                <div class="newsletter-form">
                  <form method="post" action="#">
                    <div class="form-group clearfix">
                      <input type="email" name="email" value="" placeholder="Email Address"
                             required="">
                      <button type="submit" class="theme-btn"><span
                        class="fa fa-envelope"></span></button>
                    </div>
                  </form>
                </div>
                <div class="text"> <span style="font-size:26px;">NAVOI-HD </span> К ВАШИМ УСЛУГАМ ДЛЯ ВАШЕГО БИЗНЕСА.</div>
              </div>
            </div>
          </div> -->

        </div>

      </div>
    </div>

    <!-- Footer Bottom -->
    <div class="footer-bottom">
      <div class="auto-container">
        <div class="inner clearfix">
          <div class="copyright">&copy; copyright 2021 by NAVOIY-HD.uz</div>
        </div>
      </div>
    </div>

  </footer>

    <a @click="scrollTop" class="scroll-to-target scroll-to-top" :style="`display: ${scrollBtn ? 'inline' : 'none'}`" href="#"><i class="fa fa-angle-up"></i></a>

  </div>

</template>

<script>
  export default {
    name: "Footer",
    data(){
      return {
        scrollBtn: false
      }
    },
    mounted() {
      window.addEventListener('scroll', this.handleScroll);
    },

    methods: {

      handleScroll () {

        if (window.scrollY > 70) {
          this.scrollBtn = true
        }
        else if (window.scrollY < 70) {
          this.scrollBtn = false
        }
      },

      scrollTop () {
        window.scrollTo(0, 0);
      }


    }
  }
</script>

<style scoped>

</style>
