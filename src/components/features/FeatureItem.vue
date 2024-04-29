<script setup>
import BaseHeading from "@/components/global/BaseHeading.vue";
import FeatureLayout from "@/components/features/FeatureLayout.vue";
</script>

<template>
  <FeatureLayout>
    <template #feature-layout-heading>
      <BaseHeading>
        <template #subheading-text>Features</template>
        <template #heading-text>🤔• What You Can Do?</template>
      </BaseHeading>
    </template>

    <template #feature-layout-left>
      <div class="d-grid justify-content-center">
        <slot name="feature-left-icon"></slot>
      </div>
      <div class="text-center">
        <div class="mt-3">
          <h4 class="fw-bold">
            <slot name="feature-left-heading"></slot>
          </h4>
        </div>
        <p class="mt-3">
          <slot name="feature-left-heading-desc"></slot>
        </p>
      </div>
    </template>

    <template #feature-layout-center>
      <div class="d-grid justify-content-center">
        <slot name="feature-center-icon"></slot>
      </div>
      <div class="text-center">
        <div class="mt-3">
          <h4 class="fw-bold">
            <slot name="feature-center-heading"></slot>
          </h4>
        </div>
        <p class="mt-3">
          <slot name="feature-center-heading-desc"></slot>
        </p>
      </div>
    </template>

    <template #feature-layout-right>
      <div class="d-grid justify-content-center">
        <slot name="feature-right-icon"></slot>
      </div>
      <div class="text-center">
        <div class="mt-3">
          <h4 class="fw-bold">
            <slot name="feature-right-heading"></slot>
          </h4>
        </div>
        <p class="mt-3">
          <slot name="feature-right-heading-desc"></slot>
        </p>
      </div>
    </template>
  </FeatureLayout>
</template>
