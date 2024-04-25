<script setup>
import Container from "@/components/Container.vue";
import LogoName from "@/components/icons/LogoName.vue";
</script>

<template>
  <Container>
    <div class="py-5">
      <div>
        <div class="row text-center g-0">
          <div class="col-md-4 py-3">
            <h5 class="text-primary fw-semibold">
              <slot name="footer-left"></slot>
            </h5>
            <div class="mt-5">
              <LogoName></LogoName>
            </div>
          </div>
          <div class="col-md-4 py-3">
            <h5 class="text-primary fw-semibold">
              <slot name="footer-center"></slot>
            </h5>
            <div class="mt-4 mt-md-5 d-flex gap-4 justify-content-center fs-2">
              <slot name="footer-center-sns-icon"></slot>
            </div>
          </div>
          <div class="col-md-4 py-3">
            <h5 class="text-primary fw-semibold">
              <slot name="footer-right"></slot>
            </h5>
            <p class="mt-4 mt-md-5 pt-4">
              <slot name="footer-right-desc"></slot>
            </p>
          </div>
        </div>
      </div>
    </div>
  </Container>
  <div class="bg-primary d-flex py-5 justify-content-center">
    <p class="text-white d-flex m-0 fw-semibold">
      <slot name="footer-bottom"></slot>
    </p>
  </div>
</template>
