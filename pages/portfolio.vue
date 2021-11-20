<template>
  <div>
    <Nav />
    <PageHeader title="Portfolio" />
    <GalleryPage />
    <Footer />
  </div>
</template>
<script>
  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import GalleryPage from "../components/GalleryPage";
  export default {
    components: {
      GalleryPage,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "NAVOIY-HD| Portfolio"
      }
    }
  }
</script>
