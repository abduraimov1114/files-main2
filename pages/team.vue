<template>
  <div>
    <Nav />
    <PageHeader title="Team Members" />
    <TeamPage />
    <Footer />
  </div>
</template>
<script>
  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import TeamPage from "../components/TeamPage";
  export default {
    components: {
      TeamPage,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Linoor | Team Members"
      }
    }
  }
</script>
