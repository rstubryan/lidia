<script setup>
import Navbar from "./components/Navbar.vue";
import Hero from "@/components/Hero.vue";
import Feature from "@/components/Feature.vue";
import Service from "@/components/Service.vue";
</script>

<template>
  <header>
    <Navbar></Navbar>
  </header>

  <main>
    <Hero></Hero>
    <Feature></Feature>
    <Service></Service>
  </main>
</template>

<style scoped lang="scss"></style>
