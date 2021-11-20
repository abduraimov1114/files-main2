<template>
  <div>
    <Nav />
    <PageHeader title="Services" />
    <ServicesPage />
    <Services />
    <WeWorkSection />
    <CallToActionThree />
    <Footer />
  </div>
</template>
<script>
  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Services from "../components/Services";
  import Footer from "../components/Footer";
  import ServicesPage from "../components/ServicesPage";
  import WeWorkSection from "../components/WeWorkSection";
  import CallToActionThree from "../components/CallToActionThree";
  export default {
    components: {
      CallToActionThree,
      WeWorkSection,
      ServicesPage,
      Footer,
      Services,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "NAVOIY-HD | Services"
      }
    }
  }
</script>
