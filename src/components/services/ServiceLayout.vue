<script setup>
import ContainerLayout from "@/components/global/ContainerLayout.vue";
</script>

<template>
  <ContainerLayout>
    <div class="py-3 py-sm-5">
      <div class="row">
        <slot name="service-layout-heading"></slot>
        <div class="col-12 col-xl-6">
          <slot name="service-layout-top-left"></slot>
        </div>
        <div class="col-12 col-xl-6">
          <slot name="service-layout-top-right"></slot>
        </div>
      </div>
      <div class="row">
        <div class="col-12 col-xl-6">
          <slot name="service-layout-bottom-left"></slot>
        </div>
        <div class="col-12 col-xl-6">
          <slot name="service-layout-bottom-right"></slot>
        </div>
      </div>
    </div>
  </ContainerLayout>
</template>
