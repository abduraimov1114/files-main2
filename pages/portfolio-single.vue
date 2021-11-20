<template>
  <div>
    <Nav />
    <PageHeader title="Portfolio Single" />
    <GallerySingle />
    <Footer />
  </div>
</template>
<script>
  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import GallerySingle from "../components/GallerySingle";
  export default {
    components: {
      GallerySingle,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "NAVOIY-HD | Portfolio"
      }
    }
  }
</script>
