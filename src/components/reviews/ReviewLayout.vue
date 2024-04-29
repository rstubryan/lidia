<script setup>
import ContainerLayout from "@/components/global/ContainerLayout.vue";
</script>

<template>
  <ContainerLayout>
    <div class="py-3 py-sm-5">
      <slot name="review-layout-heading"></slot>
      <div class="row mt-5">
        <div class="col-md-4 mb-4 mb-sm-0">
          <slot name="review-layout-left"></slot>
        </div>
        <div class="col-md-4 mb-4 mb-sm-0">
          <slot name="review-layout-center"></slot>
        </div>
        <div class="col-md-4 mb-4 mb-sm-0">
          <slot name="review-layout-right"></slot>
        </div>
      </div>
    </div>
  </ContainerLayout>
</template>
