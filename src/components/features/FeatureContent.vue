<script setup>
import FeatureItem from "@/components/features/FeatureItem.vue";
</script>

<template>
  <FeatureItem>
    <template #feature-left-icon>
      <button class="btn btn-primary rounded-4 shadow-lg">
        <i class="bi bi-search text-white fs-2"></i>
      </button>
    </template>
    <template #feature-left-heading>Search Book</template>
    <template #feature-left-heading-desc
      >Effortlessly find your next read with our powerful and intuitive book
      search.
    </template>
    <template #feature-center-icon>
      <button class="btn btn-primary rounded-4 shadow-lg">
        <i class="bi bi-chat text-white fs-2"></i>
      </button>
    </template>
    <template #feature-center-heading>Review Book</template>
    <template #feature-center-heading-desc
      >Discover insightful critiques and share your thoughts on diverse literary
      masterpieces effortlessly.
    </template>
    <template #feature-right-icon>
      <button class="btn btn-primary rounded-4 shadow-lg">
        <i class="bi bi-heart text-white fs-2"></i>
      </button>
    </template>
    <template #feature-right-heading>Wishlist book</template>
    <template #feature-right-heading-desc>
      Curate your literary dreams–wishlist books for future adventures and
      discoveries.
    </template>
  </FeatureItem>
</template>

<style scoped>
.btn-primary {
  --bs-btn-padding-x: 1.2rem;
  --bs-btn-padding-y: 0.5rem;
}
</style>
