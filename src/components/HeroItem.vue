<script setup>
import Container from "@/components/Container.vue";
</script>

<template>
  <Container>
    <div class="row pb-5">
      <div class="col-md-6">
        <slot name="hero-left"></slot>
      </div>
      <div class="col-md-6">
        <slot name="hero-right"></slot>
      </div>
    </div>
  </Container>
</template>
