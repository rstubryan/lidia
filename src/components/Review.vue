<script setup>
import ReviewItem from "@/components/ReviewItem.vue";
</script>

<template>
  <ReviewItem>
    <template #subheading-review>Reviews</template>
    <template #heading-review>💬• Reviews of Others</template>
    <template #review-left-desc
      >Engaging plot, vivid characters; a captivating read that lingers in your
      thoughts.
    </template>
    <template #review-left-author>Ahmad Saugi</template>
    <template #review-left-occupation>College Student</template>

    <template #review-center-desc>
      Thought-provoking narrative and rich prose. A must-read for any avid book
      lover!
    </template>
    <template #review-center-author>Muhammad Alfian</template>
    <template #review-center-occupation>School Student</template>

    <template #review-right-desc>
      Immersive storytelling! An enriching literary experience worth savoring
      and sharing.
    </template>
    <template #review-right-author>Wahyu Amirulloh</template
    ><template #review-right-occupation>ERP Developer</template>
  </ReviewItem>
</template>
