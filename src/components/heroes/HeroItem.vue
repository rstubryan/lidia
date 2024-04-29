<script setup>
import HeroLayout from "@/components/heroes/HeroLayout.vue";
</script>

<template>
  <HeroLayout>
    <template #hero-layout-left>
      <h1 class="display-1 fw-bold text-secondary">
        <slot name="hero-left-heading"></slot>
      </h1>
      <div class="py-3">
        <p class="lh-lg">
          <slot name="hero-left-heading-desc"></slot>
        </p>
      </div>
      <button class="btn btn-primary fw-semibold text-white shadow-lg">
        <slot name="hero-left-button"></slot>
      </button>
    </template>

    <template #hero-layout-right>
      <div class="col-md-6">
        <slot name="hero-right"></slot>
      </div>
    </template>
  </HeroLayout>
</template>

<style scoped>
.btn-primary {
  --bs-btn-padding-x: 2.8rem;
  --bs-btn-padding-y: 0.75rem;
}
</style>
