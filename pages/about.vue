<template>
  <div>
    <Nav />
    <PageHeader title="About" />
    <DiscoverPage />
    <Testimonial />
    <FunFacts />
    <ParallaxSection />
    <AgencySection />
    <TeamSectionTwo />
    <BrandsSectionTwo />
    <Footer />
  </div>
</template>
<script>
  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import DiscoverPage from "../components/DiscoverPage";
  import Testimonial from "../components/Testimonial";
  import FunFacts from "../components/FactSection";
  import ParallaxSection from "../components/ParallaxSection";
  import AgencySection from "../components/AgencySection";
  import TeamSectionTwo from "../components/TeamSectionTwo";
  import BrandsSectionTwo from "../components/BrandsSectionTwo";
  export default {
    components: {
      BrandsSectionTwo,
      TeamSectionTwo,
      AgencySection,
      ParallaxSection,
      FunFacts,
      Testimonial,
      DiscoverPage,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Linoor | About"
      }
    }
  }
</script>
