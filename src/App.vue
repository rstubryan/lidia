<script setup>
import Navbar from "./components/Navbar.vue";
import Hero from "@/components/Hero.vue";
import Feature from "@/components/Feature.vue";
import Service from "@/components/Service.vue";
import Review from "@/components/Review.vue";
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
  </main>
</template>

<style scoped lang="scss"></style>
