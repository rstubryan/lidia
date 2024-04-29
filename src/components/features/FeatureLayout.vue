<script setup>
import ContainerLayout from "@/components/global/ContainerLayout.vue";
</script>

<template>
  <ContainerLayout>
    <div class="row py-3 py-sm-5 pe-none">
      <slot name="feature-layout-heading"></slot>
      <div class="col-md-4 mt-5">
        <slot name="feature-layout-left"></slot>
      </div>
      <div class="col-md-4 mt-5">
        <slot name="feature-layout-center"></slot>
      </div>
      <div class="col-md-4 mt-5">
        <slot name="feature-layout-right"></slot>
      </div>
    </div>
  </ContainerLayout>
</template>
