<template>
  <div>
    <Nav />
    <PageHeader title="Наш прайс" />
    <TestimonialPage />
    <Footer />
  </div>
</template>
<script>
  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import TestimonialPage from "../components/TestimonialPage";
  export default {
    components: {
      TestimonialPage,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Linoor | Testimonials"
      }
    }
  }
</script>
