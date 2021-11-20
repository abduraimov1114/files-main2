<template>
  <div>
    <Nav />
    <PageHeader title="UI/UX Designing" />
    <ServiceDetails />
    <CallToActionThree />
    <Footer />
  </div>
</template>
<script>
  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import CallToActionThree from "../components/CallToActionThree";
  import ServiceDetails from "../components/ServiceDetails";
  export default {
    components: {
      ServiceDetails,
      CallToActionThree,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Linoor | UI/UX Designing"
      }
    }
  }
</script>
