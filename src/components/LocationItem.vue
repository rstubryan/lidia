<script setup>
import Container from "@/components/Container.vue";
</script>

<template>
  <Container>
    <div class="py-3">
      <div>
        <div class="py-2">
          <span class="text-primary fw-bold text-uppercase">
            <slot name="subheading-location"></slot>
          </span>
        </div>
        <div>
          <h2 class="fw-bold text-secondary">
            <slot name="heading-location"></slot>
          </h2>
        </div>
      </div>
      <div class="row">
        <div class="col"></div>
      </div>
    </div>
  </Container>
</template>
