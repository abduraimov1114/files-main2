<template>
  <section class="error-section">
    <div class="auto-container">
      <div class="content">
        <div class="big-text">
          <img src="/images/icons/404-image.png" id="error-404" class="img-fluid" alt="">
        </div>
        <h2>Sorry We Can't Find That Page!</h2>
        <div class="text">The page you are looking for was moved, removed, renamed or never existed.</div>
        <div class="error-form">
          <form method="post" action="#">
            <div class="form-group clearfix">
              <input type="search" name="email" value="" placeholder="Search here" required="">
              <button type="submit" class="theme-btn"><span class="flaticon-search"></span></button>
            </div>
          </form>
        </div>
        <div class="link-box">
          <nuxt-link class="theme-btn btn-style-one" to="/about">
            <i class="btn-curve"></i>
            <span class="btn-title">Back to home</span>
          </nuxt-link>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "ErrorPage"
    }
</script>

<style scoped>

</style>
