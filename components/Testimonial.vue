<template>
  <section class="testimonials-section">
    <div class="auto-container">
      <div class="sec-title">
        <h3>Комментарии от лучших<span class="dot">.</span></h3>
      </div>
      <div class="carousel-box">
        <div class="testimonials-carousel">
          <carousel :autoplay="true" :margin="30" :responsive="{0: {items: 1},600: {items: 1},768: {items: 1},992: {items: 2},1200: {items: 2}}">
          <div class="testi-block">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="info">
                <div class="image"><a href="/team"><img src="/images/resource/author-1.jpg"
                                                            alt=""></a></div>
                <div class="name">Adver.uz</div>
                <div class="designation">комментарий</div>
              </div>
              <div class="text">555There are many variations of passages of lorem ipsum available but the
                majority have suffered alteration in some form, by injected humour, or randomised
                words which don't look even slightly believable.</div>
            </div>
          </div>
          <div class="testi-block">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="info">
                <div class="image"><a href="/team"><img src="/images/resource/author-2.jpg"
                                                            alt=""></a></div>
                <div class="name">NavoiyATX</div>
                <div class="designation">комментарий</div>
              </div>
              <div class="text">There are many variations of passages of lorem ipsum available but the
                majority have suffered alteration in some form, by injected humour, or randomised
                words which don't look even slightly believable.</div>
            </div>
          </div>
          <div class="testi-block">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="info">
                <div class="image"><a href="/team"><img src="/images/resource/author-3.jpg"
                                                            alt=""></a></div>
                <div class="name">UZLED</div>
                <div class="designation">комментарий</div>
              </div>
              <div class="text">There are many variations of passages of lorem ipsum available but the
                majority have suffered alteration in some form, by injected humour, or randomised
                words which don't look even slightly believable.</div>
            </div>
          </div>
          <div class="testi-block">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="info">
                <div class="image"><a href="/team"><img src="/images/resource/author-1.jpg"
                                                            alt=""></a></div>
                <div class="name">Qizilqum semenet</div>
                <div class="designation">комментарий</div>
              </div>
              <div class="text">There are many variations of passages of lorem ipsum available but the
                majority have suffered alteration in some form, by injected humour, or randomised
                words which don't look even slightly believable.</div>
            </div>
          </div>
          <div class="testi-block">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="info">
                <div class="image"><a href="/team"><img src="/images/resource/author-2.jpg"
                                                            alt=""></a></div>
                <div class="name">Yangi Hayot</div>
                <div class="designation">комментарий</div>
              </div>
              <div class="text">There are many variations of passages of lorem ipsum available but the
                majority have suffered alteration in some form, by injected humour, or randomised
                words which don't look even slightly believable.</div>
            </div>
          </div>
          <div class="testi-block">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="info">
                <div class="image"><a href="/team"><img src="/images/resource/author-3.jpg"
                                                            alt=""></a></div>
                <div class="name">Tinchlik.uz</div>
                <div class="designation">комментарий</div>
              </div>
              <div class="text">There are many variations of passages of lorem ipsum available but the
                majority have suffered alteration in some form, by injected humour, or randomised
                words which don't look even slightly believable.</div>
            </div>
          </div>
          </carousel>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "Testimonial"
    }
</script>

<style scoped>

</style>
