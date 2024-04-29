<script setup>
import ContainerLayout from "@/components/global/ContainerLayout.vue";
</script>

<template>
  <ContainerLayout>
    <div class="row py-5">
      <div class="col-md-4">
        <slot name="footer-layout-left"> </slot>
      </div>
      <div class="col-md-4">
        <slot name="footer-layout-center"> </slot>
      </div>
      <div class="col-md-4">
        <slot name="footer-layout-right"> </slot>
      </div>
    </div>
  </ContainerLayout>
</template>
