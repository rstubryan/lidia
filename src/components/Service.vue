<script setup>
import ServiceItem from "@/components/ServiceItem.vue";
</script>

<template>
  <ServiceItem>
    <template #subheading-service> Services </template>
    <template #heading-service> 🚀• The Services for You </template>
    <template #service-top-left></template>
    <template #service-top-right>
      <span class="text-primary">Rent</span> your favorite book fairly easy on
      <span class="text-primary">Lidia!</span></template
    >
    <template #service-top-right-desc>
      Viewing, rent, and organize your favorite books has never been easier. An
      integrated digital library rent that’s simple to use, Lidia lets you spend
      less time managing your work and more time actually doing it! <br />
      Effortless rentals, personalized shelves—Lidia transforms book management,
      enhancing your reading experience~
    </template>
    <template #service-bottom-left>
      Quick Book Rentals: <span class="text-primary">Dive</span> into
      <span class="text-primary">Reading</span> Instantly</template
    ><template #service-bottom-left-desc>
      Discover instant literary delight. Access a vast library, borrow your
      favorite reads, and dive into captivating stories within minutes. Reading
      made quick and easy, just a click away! <br />
      Unlock a world of stories effortlessly. Browse genres, choose, rent in
      minutes. Seamlessly manage your reading adventures with our intuitive
      platform~
    </template>
    <template #service-bottom-right></template>
  </ServiceItem>
</template>
