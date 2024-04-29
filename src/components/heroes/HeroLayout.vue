<script setup>
import ContainerLayout from "@/components/global/ContainerLayout.vue";
</script>

<template>
  <ContainerLayout>
    <div class="row">
      <div class="col-md-6 py-5">
        <slot name="hero-layout-left"></slot>
      </div>
      <div class="col-md-6">
        <slot name="hero-layout-right"></slot>
      </div>
    </div>
  </ContainerLayout>
</template>
