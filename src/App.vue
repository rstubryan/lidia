<script setup>
import HeroContent from "@/components/heroes/HeroContent.vue";
import FeatureContent from "@/components/features/FeatureContent.vue";
import ServiceContent from "@/components/services/ServiceContent.vue";
import ReviewContent from "@/components/reviews/ReviewContent.vue";
import LocationContent from "@/components/locations/LocationContent.vue";
import FooterContent from "@/components/global/FooterContent.vue";
import BackgroundCover from "@/components/icons/CoverBackground.vue";
import ComponentNavbar from "@/components/global/ComponentNavbar.vue";
</script>

<template>
  <div class="d-none d-lg-block z-n1 position-absolute top-0 start-50">
    <BackgroundCover />
  </div>

  <header>
    <ComponentNavbar></ComponentNavbar>
  </header>

  <main>
    <HeroContent></HeroContent>
    <FeatureContent></FeatureContent>
    <ServiceContent></ServiceContent>
    <ReviewContent></ReviewContent>
    <LocationContent></LocationContent>
  </main>

  <footer>
    <FooterContent></FooterContent>
  </footer>
</template>

<style scoped lang="scss"></style>
