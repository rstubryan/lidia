<script setup>
import Container from "@/components/Container.vue";
</script>

<template>
  <Container>
    <div class="py-3">
      <div>
        <div class="py-2">
          <span class="text-primary fw-bold text-uppercase">
            <slot name="subheading-feature"></slot>
          </span>
        </div>
        <div>
          <h2 class="fw-bold text-secondary">
            <slot name="heading-feature"></slot>
          </h2>
        </div>
      </div>
      <div class="row py-5 g-5 pe-none">
        <div class="col-md-4">
          <div class="d-grid justify-content-center mt-3">
            <slot name="feature-left-icon"></slot>
          </div>
          <div class="text-center">
            <div class="mt-3">
              <h4 class="fw-bold">
                <slot name="feature-left-heading"></slot>
              </h4>
            </div>
            <p class="mt-3">
              <slot name="feature-left-heading-desc"></slot>
            </p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="d-grid justify-content-center mt-3">
            <slot name="feature-center-icon"></slot>
          </div>
          <div class="text-center">
            <div class="mt-3">
              <h4 class="fw-bold">
                <slot name="feature-center-heading"></slot>
              </h4>
            </div>
            <p class="mt-3">
              <slot name="feature-center-heading-desc"></slot>
            </p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="d-grid justify-content-center mt-3">
            <slot name="feature-right-icon"></slot>
          </div>
          <div class="text-center">
            <div class="mt-3">
              <h4 class="fw-bold">
                <slot name="feature-right-heading"></slot>
              </h4>
            </div>
            <p class="mt-3">
              <slot name="feature-right-heading-desc"></slot>
            </p>
          </div>
        </div>
      </div>
    </div>
  </Container>
</template>
