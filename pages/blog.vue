<template>
  <div>
    <Nav />
    <PageHeader title="Blog Sidebar" />
    <BlogSidebar />
    <Footer />
  </div>
</template>
<script>
  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import BlogSidebar from "../components/BlogSidebar";
  export default {
    components: {
      BlogSidebar,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Linoor | Blog Sidebar"
      }
    }
  }
</script>
