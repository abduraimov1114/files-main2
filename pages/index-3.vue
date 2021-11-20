<template>
  <div>
    <NavTwo />
    <BannerThree />
    <CallToActionTwo />
    <DiscoverSection />
    <ServicesThree />
    <FeaturesTwo />
    <WeWorkSection />
    <TestimonialCarousel />
    <AboutTwo />
    <GalleryCarouselTwo />
    <QuoteSectionTwo />
    <MapSection />
    <BrandsSectionTwo />
    <Footer />
  </div>
</template>


<script>
  import NavTwo from "../components/NavTwo";
  import Footer from "../components/Footer";
  import BannerThree from "../components/BannerThree";
  import CallToActionTwo from "../components/CallToActionTwo";
  import DiscoverSection from "../components/DiscoverSection";
  import ServicesThree from "../components/ServicesThree";
  import FeaturesTwo from "../components/FeaturesTwo";
  import WeWorkSection from "../components/WeWorkSection";
  import TestimonialCarousel from "../components/TestimonialCarousel";
  import AboutTwo from "../components/AboutTwo";
  import GalleryCarouselTwo from "../components/GalleryCarouselTwo";
  import QuoteSectionTwo from "../components/QuoteSectionTwo";
  import MapSection from "../components/MapSection";
  import BrandsSectionTwo from "../components/BrandsSectionTwo";
  export default {
    components: {
      BrandsSectionTwo,
      MapSection,
      QuoteSectionTwo,
      GalleryCarouselTwo,
      AboutTwo,
      TestimonialCarousel,
      WeWorkSection,
      FeaturesTwo,
      ServicesThree,
      DiscoverSection,
      CallToActionTwo,
      BannerThree,
      NavTwo,
      Footer,
    },
    head(){
      return {
        title: "Linoor | Home 3"
      }
    }
  }
</script>
