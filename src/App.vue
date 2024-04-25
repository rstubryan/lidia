<script setup>
import Navbar from "./components/Navbar.vue";
import Hero from "@/components/Hero.vue";
import Feature from "@/components/Feature.vue";
import Service from "@/components/Service.vue";
import Review from "@/components/Review.vue";
import Location from "@/components/Location.vue";
import Footer from "@/components/Footer.vue";
</script>

<template>
  <header>
    <Navbar></Navbar>
  </header>

  <main>
    <Hero></Hero>
    <Feature></Feature>
    <Service></Service>
    <Review></Review>
    <Location></Location>
  </main>

  <footer>
    <Footer></Footer>
  </footer>
</template>

<style scoped lang="scss"></style>
