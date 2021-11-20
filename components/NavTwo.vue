<template>
  <header :class="`main-header header-style-two ${sticky ? 'fixed-header' : ''}`">

    <!-- Header Upper -->
    <div class="header-upper">
      <div class="inner-container clearfix">
        <!--Logo-->
        <div class="logo-box">
          <div class="logo"><a href="/" title="Linoor - DIgital Agency Template"><img
            src="/images/logo.png" id="thm-logo" alt="Linoor - Digital Agency HTML Template"
            title="Linoor - DIgital Agency Template"></a></div>
        </div>
        <div class="nav-outer clearfix">
          <!--Mobile Navigation Toggler-->
          <div class="mobile-nav-toggler">
            <span @click="mobileToggle = !mobileToggle" class="icon flaticon-menu-2"></span><span class="txt">Menu</span>
          </div>

          <!-- Main Menu -->
          <nav class="main-menu navbar-expand-md navbar-light">
            <div class="collapse navbar-collapse show clearfix">
              <ul class="navigation clearfix">
                <li class="current dropdown"><a href="/">Home</a>
                  <ul>
                    <li><nuxt-link to="/">Home Style 01</nuxt-link></li>
                    <li><nuxt-link to="/index-2">Home Style 02</nuxt-link></li>
                    <li><nuxt-link to="/index-3">Home Style 03</nuxt-link></li>
                  </ul>
                </li>
                <li><nuxt-link to="/about">About Us</nuxt-link></li>
                <li class="dropdown"><a href="/team">Pages</a>
                  <ul>
                    <li><nuxt-link to="/team">Our Team</nuxt-link></li>
                    <li><nuxt-link to="/testimonials">Testimonials</nuxt-link></li>
                    <li><nuxt-link to="/faqs">FAQs</nuxt-link></li>
                    <li><nuxt-link to="/not-found">404 Page</nuxt-link></li>
                  </ul>
                </li>
                <li class="dropdown"><nuxt-link to="/services">Services</nuxt-link>
                  <ul>
                    <li><nuxt-link to="/services">All Services</nuxt-link></li>
                    <li><nuxt-link to="/web-development">Website Development</nuxt-link></li>
                    <li><nuxt-link to="/graphic-designing">Graphic Designing</nuxt-link></li>
                    <li><nuxt-link to="/digital-marketing">Digital Marketing</nuxt-link></li>
                    <li><nuxt-link to="/seo">SEO & Content Writting</nuxt-link></li>
                    <li><nuxt-link to="/app-development">App Development</nuxt-link></li>
                    <li><nuxt-link to="/ui-designing">UI/UX Designing</nuxt-link></li>
                  </ul>
                </li>
                <li class="dropdown"><nuxt-link to="/portfolio">Portfolio</nuxt-link>
                  <ul>
                    <li><nuxt-link to="/portfolio">Portfolio</nuxt-link></li>
                    <li><nuxt-link to="/portfolio-single">Portfolio Single 01</nuxt-link></li>
                    <li><nuxt-link to="/portfolio-single-2">Portfolio Single 02</nuxt-link></li>
                  </ul>
                </li>
                <li class="dropdown"><nuxt-link to="/blog-grid">Blog</nuxt-link>
                  <ul>
                    <li><nuxt-link to="/blog">Blog Sidebar</nuxt-link></li>
                    <li><nuxt-link to="/blog-grid">Blog Grid View</nuxt-link></li>
                    <li><nuxt-link to="/blog-single">Blog Single</nuxt-link></li>
                  </ul>
                </li>
                <li><nuxt-link to="/contact">Contact</nuxt-link></li>
              </ul>
            </div>
          </nav>
        </div>

        <div class="other-links clearfix">
          <div class="link-box">
            <div class="call-us">
              <a class="link" href="tel:6668880000">
                <span class="icon"></span>
                <span class="sub-text">Call Anytime</span>
                <span class="number">666 888 0000</span>
              </a>
            </div>
          </div>
        </div>

      </div>
    </div>
    <!--End Header Upper-->
    <nav class="mobile-nav__container">
      <!-- content is loading via js -->

      <div :class="`collapse navbar-collapse ${mobileToggle ? 'show' : ''} clearfix`">
        <ul class="navigation clearfix">
          <li class="dropdown"><a href="#">Home<div class="dropdown-btn"><span class="fa fa-angle-right"></span></div></a>
            <ul class="sub-menu">
              <li><nuxt-link to="/">Home Style 01</nuxt-link></li>
              <li><nuxt-link to="/index-2">Home Style 02</nuxt-link></li>
              <li><nuxt-link to="/index-3">Home Style 03</nuxt-link></li>
            </ul>
          </li>
          <li><nuxt-link to="/about">About Us</nuxt-link></li>
          <li class="dropdown"><a href="#">Pages<div class="dropdown-btn"><span class="fa fa-angle-right"></span></div></a>
            <ul class="sub-menu">
              <li><nuxt-link to="/team">Our Team</nuxt-link></li>
              <li><nuxt-link to="/testimonials">Testimonials</nuxt-link></li>
              <li><nuxt-link to="/faqs">FAQs</nuxt-link></li>
              <li><nuxt-link to="/not-found">404 Page</nuxt-link></li>
            </ul>
          </li>
          <li class="dropdown"><nuxt-link to="#">Services<div class="dropdown-btn"><span class="fa fa-angle-right"></span></div></nuxt-link>
            <ul class="sub-menu">
              <li><nuxt-link to="/services">All Services</nuxt-link></li>
              <li><nuxt-link to="/web-development">Website Development</nuxt-link></li>
              <li><nuxt-link to="/graphic-designing">Graphic Designing</nuxt-link></li>
              <li><nuxt-link to="/digital-marketing">Digital Marketing</nuxt-link></li>
              <li><nuxt-link to="/seo">SEO & Content Writting</nuxt-link></li>
              <li><nuxt-link to="/app-development">App Development</nuxt-link></li>
              <li><nuxt-link to="/ui-designing">UI/UX Designing</nuxt-link></li>
            </ul>
          </li>
          <li class="dropdown"><nuxt-link to="#">Portfolio<div class="dropdown-btn"><span class="fa fa-angle-right"></span></div></nuxt-link>
            <ul class="sub-menu">
              <li><nuxt-link to="/portfolio">Portfolio</nuxt-link></li>
              <li><nuxt-link to="/portfolio-single">Portfolio Single 01</nuxt-link></li>
              <li><nuxt-link to="/portfolio-single-2">Portfolio Single 02</nuxt-link></li>
            </ul>
          </li>
          <li class="dropdown"><nuxt-link to="#">Blog<div class="dropdown-btn"><span class="fa fa-angle-right"></span></div></nuxt-link>
            <ul class="sub-menu">
              <li><nuxt-link to="/blog">Blog Sidebar</nuxt-link></li>
              <li><nuxt-link to="/blog-grid">Blog Grid View</nuxt-link></li>
              <li><nuxt-link to="/blog-single">Blog Single</nuxt-link></li>
            </ul>
          </li>
          <li><nuxt-link to="/contact">Contact</nuxt-link></li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script>
  export default {
    name: "Nav",
    data(){
      return {
        sticky: false,
        mobileToggle: false
      }
    },
    mounted() {
      window.addEventListener('scroll', this.handleScroll);

      const mobileNav = document.querySelector('.mobile-nav__container');
      const dropdownMenu = mobileNav.querySelectorAll('.dropdown');
      
      for (let i = 0; i < dropdownMenu.length; i++) {
          dropdownMenu[i].addEventListener("click", function() {
          this.classList.toggle('open');
          this.classList.toggle('current');
          });
      }
      
    },
    methods: {

      handleScroll() {
        if (window.scrollY > 70) {
          this.sticky = true
        } else if (window.scrollY < 70) {
          this.sticky = false
        }
      },
    }
  }
</script>

<style scoped>

</style>
