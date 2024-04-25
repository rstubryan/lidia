<script setup>
import Container from "@/components/Container.vue";
</script>

<template>
  <Container>
    <div class="py-5">
      <div>
        <div class="py-2">
          <span class="text-primary fw-bold text-uppercase">
            <slot name="subheading-service"></slot>
          </span>
        </div>
        <div>
          <h2 class="fw-bold text-secondary">
            <slot name="heading-service"></slot>
          </h2>
        </div>
      </div>
      <div class="row py-3 g-5">
        <div class="col-md-6">
          <slot name="service-top-left"></slot>
        </div>
        <div class="col-md-6">
          <div class="">
            <h4>
              <slot name="service-top-right"></slot>
            </h4>
            <p><slot name="service-top-right-desc"></slot>/</p>
          </div>
        </div>
      </div>
      <div class="row py-3 g-5">
        <div class="col-md-6">
          <div>
            <h4>
              <slot name="service-bottom-left"></slot>
            </h4>
            <p><slot name="service-bottom-left-desc"></slot></p>
          </div>
        </div>
        <div class="col-md-6"><slot name="service-bottom-right"></slot></div>
      </div>
    </div>
  </Container>
</template>
