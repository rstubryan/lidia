<script setup>
import FooterItem from "@/components/global/FooterItem.vue";
</script>

<template>
  <FooterItem>
    <template #footer-left>Managed By</template>
    <template #footer-center>Social Media</template>
    <template #footer-center-sns-icon>
      <a href="" class="mt-3"> <i class="bi bi-twitter-x"></i></a>
      <a href="" class="mt-3"> <i class="bi bi-instagram"></i></a>
      <a href="" class="mt-3"> <i class="bi bi-facebook"></i></a>
    </template>
    <template #footer-right>Slogan</template>
    <template #footer-right-desc>#RentFavBooks</template
    ><template #footer-bottom>© 2024 Lidia. All rights reserved.</template>
  </FooterItem>
</template>
