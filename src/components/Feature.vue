<script setup>
import FeatureItem from "@/components/FeatureItem.vue";
</script>

<template>
  <FeatureItem>
    <template #subheading-feature> Features </template>
    <template #heading-feature> 🤔• What You Can Do? </template>
    <template #feature-left>
      <div class="d-grid justify-content-center mt-3">
        <button class="btn btn-primary rounded-4 shadow-lg">
          <i class="bi bi-search text-white fs-2"></i>
        </button>
      </div>
      <div class="text-center">
        <div class="mt-3">
          <h4 class="fw-bold">Search Book</h4>
        </div>
        <p class="mt-3">
          Effortlessly find your next read with our powerful and intuitive book
          search.
        </p>
      </div>
    </template>
    <template #feature-center>
      <div class="d-grid justify-content-center mt-3">
        <button class="btn btn-primary rounded-4 shadow-lg">
          <i class="bi bi-chat text-white fs-2"></i>
        </button>
      </div>
      <div class="text-center">
        <div class="mt-3">
          <h4 class="fw-bold">Review Book</h4>
        </div>
        <p class="mt-3">
          Discover insightful critiques and share your thoughts on diverse
          literary masterpieces effortlessly.
        </p>
      </div>
    </template>
    <template #feature-right>
      <div class="d-grid justify-content-center mt-3">
        <button class="btn btn-primary rounded-4 shadow-lg">
          <i class="bi bi-heart text-white fs-2"></i>
        </button>
      </div>
      <div class="text-center">
        <div class="mt-3">
          <h4 class="fw-bold">Wishlist book</h4>
        </div>
        <p class="mt-3">
          Curate your literary dreams–wishlist books for future adventures and
          discoveries.
        </p>
      </div>
    </template>
  </FeatureItem>
</template>

<style scoped>
.btn-primary {
  --bs-btn-padding-x: 1.2rem;
  --bs-btn-padding-y: 0.5rem;
}
</style>
