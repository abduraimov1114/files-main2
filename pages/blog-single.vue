<template>
  <div>
    <Nav />
    <PageHeader title="Blog Single" />
    <BlogSingle />
    <Footer />
  </div>
</template>
<script>
  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import BlogSingle from "../components/BlogSingle";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      PageHeader,
      BlogSingle,
      Nav
    },
    head(){
      return {
        title: "Linoor | Blog Single"
      }
    }
  }
</script>
