<template>
  <section class="page-banner">
    <div class="image-layer" style="background-image:url(/images/background/image-7.jpg);"></div>
    <div class="shape-1"></div>
    <div class="shape-2"></div>
    <div class="banner-inner">
      <div class="auto-container">
        <div class="inner-container clearfix">
          <h1>{{ title }}</h1>
          <div class="page-nav" style="display:none;">
            <ul class="bread-crumb clearfix">
              <li><nuxt-link to="/">Home</nuxt-link></li>
              <li class="active">{{ title }}</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: "PageHeader",
    props: {
      title: {
        type: String
      }
    }

  }
</script>

<style scoped>

</style>
