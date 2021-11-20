<template>
  <div>
    <Nav />
    <PageHeader title="404 Error" />
    <ErrorPage />
    <Footer />
  </div>
</template>
<script>
  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import ErrorPage from "../components/ErrorPage";
  export default {
    components: {
      ErrorPage,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "NAVOIY-HD | 404 Error"
      }
    }
  }
</script>
