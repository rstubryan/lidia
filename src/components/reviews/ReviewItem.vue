<script setup>
import BaseCard from "@/components/global/BaseCard.vue";
import BaseHeading from "@/components/global/BaseHeading.vue";
import ReviewLayout from "@/components/reviews/ReviewLayout.vue";
</script>

<template>
  <ReviewLayout>
    <template #review-layout-heading>
      <BaseHeading>
        <template #subheading-text> Reviews </template>
        <template #heading-text> 💬• Reviews of Others </template>
      </BaseHeading>
    </template>

    <template #review-layout-left>
      <BaseCard>
        <template #review-desc>
          <slot name="review-left-desc"></slot>
        </template>
        <template #review-author>
          <slot name="review-left-author"></slot>
        </template>
        <template #review-occupation>
          <slot name="review-left-occupation"></slot>
        </template>
      </BaseCard>
    </template>
    <template #review-layout-center>
      <BaseCard>
        <template #review-desc>
          <slot name="review-center-desc"></slot>
        </template>
        <template #review-author>
          <slot name="review-center-author"></slot>
        </template>
        <template #review-occupation>
          <slot name="review-center-occupation"></slot>
        </template>
      </BaseCard>
    </template>
    <template #review-layout-right>
      <BaseCard>
        <template #review-desc>
          <slot name="review-right-desc"></slot>
        </template>
        <template #review-author>
          <slot name="review-right-author"></slot>
        </template>
        <template #review-occupation>
          <slot name="review-right-occupation"></slot>
        </template>
      </BaseCard>
    </template>
  </ReviewLayout>
</template>
