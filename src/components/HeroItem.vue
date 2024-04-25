<script setup>
import Container from "@/components/Container.vue";
</script>

<template>
  <Container>
    <div class="row pb-5">
      <div class="col-md-6">
        <div class="py-2">
          <h1 class="display-1 fw-bold text-secondary">
            <slot name="hero-left-heading"></slot>
          </h1>
          <div class="py-3">
            <p class="lh-lg mt-3">
              <slot name="hero-left-heading-desc"></slot>
            </p>
          </div>
          <button class="btn btn-primary fw-semibold text-white shadow-lg">
            <slot name="hero-left-button"></slot>
          </button>
        </div>
      </div>

      <div class="col-md-6">
        <slot name="hero-right"></slot>
      </div>
    </div>
  </Container>
</template>

<style scoped>
.btn-primary {
  --bs-btn-padding-x: 2.8rem;
  --bs-btn-padding-y: 0.75rem;
}
</style>
