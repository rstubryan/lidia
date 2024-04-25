<script>
import { defineComponent } from "vue";
import HeroItem from "@/components/HeroItem.vue";

export default defineComponent({
  components: { HeroItem },
});
</script>

<template>
  <HeroItem>
    <template #hero-left-heading>
      Search & review your
      <span class="text-primary text-decoration-underline link-offset-2"
        >fav book</span
      >
    </template>

    <template #hero-left-heading-desc>
      Embark on a literary journey like never before with our revolutionary
      library application! Introducing a seamless experience that transcends
      traditional boundaries, where you can effortlessly search your favorite
      books.✨
    </template>

    <template #hero-left-button>
      Start now <i class="bi bi-arrow-right"></i>
    </template>

    <template #hero-right>
      <div>
        <h1>Hello</h1>
        <BooksHero></BooksHero>
      </div>
    </template>
  </HeroItem>
</template>

<style scoped></style>
