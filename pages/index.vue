<template>
  <div>
    <Nav />
    <Banner />
    <Services />
    <About />
    <LiveSection />
    <WedoSection />
    <GallerySection />
    <FactSection />
    <TrustedSection />
    <TeamSection />
    <ParallaxSection />
    <BrandsSection />
    <AgencySection />
    <BlogSection />
    <CallToAction />
    <Footer />
  </div>
</template>
<script>
  import Nav from "../components/Nav";
  import Banner from "../components/Banner";
  import Services from "../components/Services";
  import About from "../components/About";
  import LiveSection from "../components/LiveSection";
  import WedoSection from "../components/WedoSection";
  import GallerySection from "../components/GallerySection";
  import FactSection from "../components/FactSection";
  import TrustedSection from "../components/TrustedSection";
  import TeamSection from "../components/TeamSection";
  import ParallaxSection from "../components/ParallaxSection";
  import BrandsSection from "../components/BrandsSection";
  import AgencySection from "../components/AgencySection";
  import BlogSection from "../components/BlogSection";
  import CallToAction from "../components/CallToAction";
  import Footer from "../components/Footer";

  export default {
    components: {
      Footer,
      CallToAction,
      BlogSection,
      AgencySection,
      BrandsSection,
      ParallaxSection,
      TeamSection,
      TrustedSection,
      FactSection,
      GallerySection,
      WedoSection,
      LiveSection,
      About,
      Services,
      Banner,
      Nav

    }
  }
</script>
