<script setup>
import BaseHeading from "@/components/global/BaseHeading.vue";
import LocationLayout from "@/components/locations/LocationLayout.vue";
</script>

<template>
  <LocationLayout>
    <template #location-layout-heading>
      <BaseHeading>
        <template #subheading-text> Location </template>
        <template #heading-text> 🗺• Our Library Location </template>
      </BaseHeading>
    </template>
    <template #location-layout-images>
      <h1 class="text-primary">Hello World</h1>
    </template>
  </LocationLayout>
</template>
