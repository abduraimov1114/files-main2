<template>
  <section class="testimonials-section-two">
    <div class="image-layer" style="background-image: url(/images/background/image-6.jpg);"></div>
    <div class="auto-container">
      <div class="carousel-box">
        <div class="testimonials-carousel-two">
          <no-ssr>
          <carousel :items="1">
          <div class="testi-block-two">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="text">This is due to their excellent service, competitive pricing and
                customer support. It’s throughly refresing to get such a personal touch.</div>
              <div class="info">
                <div class="name">Christine Eve</div>
              </div>
            </div>
          </div>
          <div class="testi-block-two">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="text">This is due to their excellent service, competitive pricing and
                customer support. It’s throughly refresing to get such a personal touch.</div>
              <div class="info">
                <div class="name">Christine Eve</div>
              </div>
            </div>
          </div>
          <div class="testi-block-two">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="text">This is due to their excellent service, competitive pricing and
                customer support. It’s throughly refresing to get such a personal touch.</div>
              <div class="info">
                <div class="name">Christine Eve</div>
              </div>
            </div>
          </div>
          </carousel>
          </no-ssr>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "TestimonialCarousel"
    }
</script>

<style scoped>

</style>
