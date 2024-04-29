<script setup>
import ContainerLayout from "@/components/global/ContainerLayout.vue";
</script>

<template>
  <ContainerLayout>
    <div class="py-3 py-sm-5">
      <slot name="location-layout-heading"></slot>
      <div class="row my-5">
        <div class="col-12">
          <slot name="location-layout-images"></slot>
        </div>
      </div>
    </div>
  </ContainerLayout>
</template>
