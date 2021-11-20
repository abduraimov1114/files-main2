<template>
  <div>
    <Nav />
    <PageHeader title="Portfolio Single 2" />
    <GallerySingleTwo />
    <Footer />
  </div>
</template>
<script>
  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import GallerySingleTwo from "../components/GallerySingleTwo";
  export default {
    components: {
      GallerySingleTwo,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "NAVOIY-HD| Portfolio 2"
      }
    }
  }
</script>
