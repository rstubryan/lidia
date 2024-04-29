<script setup>
import LogoName from "@/components/icons/LogoName.vue";
import FooterLayout from "@/components/global/FooterLayout.vue";
</script>

<template>
  <FooterLayout>
    <template #footer-layout-left>
      <h5 class="text-primary text-center fw-semibold">
        <slot name="footer-left"></slot>
      </h5>
      <div class="mt-5 mb-5 mt-sm-5 mb-sm-0 text-center">
        <LogoName></LogoName>
      </div>
    </template>

    <template #footer-layout-center>
      <h5 class="text-primary text-center fw-semibold">
        <slot name="footer-center"></slot>
      </h5>
      <div
        class="mt-4 mb-5 mt-sm-5 mb-sm-0 d-flex gap-4 justify-content-center fs-2"
      >
        <slot name="footer-center-sns-icon"></slot>
      </div>
    </template>

    <template #footer-layout-right>
      <h5 class="text-primary text-center fw-semibold">
        <slot name="footer-right"></slot>
      </h5>
      <p class="mt-4 mb-5 mt-sm-5 mb-sm-0 text-center pt-4">
        <slot name="footer-right-desc"></slot>
      </p>
    </template>
  </FooterLayout>

  <article class="bg-primary d-flex py-5 justify-content-center">
    <p class="text-white d-flex m-0 fw-semibold">
      <slot name="footer-bottom"></slot>
    </p>
  </article>
</template>
