<script setup>
import Container from "@/components/Container.vue";
</script>

<template>
  <Container>
    <div class="py-5">
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
        <div class="col-md-4"><slot name="feature-left"></slot></div>
        <div class="col-md-4"><slot name="feature-center"></slot></div>
        <div class="col-md-4"><slot name="feature-right"></slot></div>
      </div>
    </div>
  </Container>
</template>
