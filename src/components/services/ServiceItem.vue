<script setup>
import BaseHeading from "@/components/global/BaseHeading.vue";
import ServiceLayout from "@/components/services/ServiceLayout.vue";
import ServicesLeft from "@/components/icons/ServicesLeft.vue";
import ServicesRight from "@/components/icons/ServicesRight.vue";
</script>

<template>
  <ServiceLayout>
    <template #service-layout-heading>
      <BaseHeading>
        <template #subheading-text> Services </template>
        <template #heading-text> 🚀• The Services for You </template>
      </BaseHeading>
    </template>

    <template #service-layout-top-left>
      <ServicesLeft></ServicesLeft>
    </template>
    <template #service-layout-top-right>
      <article class="my-0 my-sm-5 mt-3 pe-0 pe-sm-5">
        <h4>
          <slot name="service-top-right"></slot>
        </h4>
        <p class="lh-lg"><slot name="service-top-right-desc"></slot></p>
      </article>
    </template>
    <template #service-layout-bottom-right>
      <ServicesRight></ServicesRight>
    </template>
    <template #service-layout-bottom-left>
      <article class="my-0 my-sm-5 mt-3 pe-0 pe-sm-5">
        <h4>
          <slot name="service-bottom-left"></slot>
        </h4>
        <p class="lh-lg"><slot name="service-bottom-left-desc"></slot></p>
      </article>
    </template>
  </ServiceLayout>
</template>
