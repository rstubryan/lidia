<script>
import { defineComponent } from "vue";
import HeroItem from "@/components/HeroItem.vue";
import Container from "@/components/Container.vue";
import BooksHero from "./icons/BooksHero.vue";

export default defineComponent({
  components: { Container, HeroItem },
});
</script>

<template>
  <HeroItem>
    <template #hero-left>
      <div class="py-2">
        <h1 class="display-1 fw-bold text-secondary">
          Search & review your
          <span class="text-primary text-decoration-underline link-offset-2"
            >fav book</span
          >
          effortlessly
        </h1>
        <div class="py-3">
          <p class="lh-lg">
            Embark on a literary journey like never before with our
            revolutionary library application! Introducing a seamless experience
            that transcends traditional boundaries, where you can effortlessly
            search your favorite books.✨
          </p>
        </div>
        <button class="btn btn-primary fw-semibold text-white shadow-lg">
          Start now <i class="bi bi-arrow-right"></i>
        </button>
      </div>
    </template>

    <template #hero-right>
      <div>
        <h1>Hello</h1>
        <BooksHero></BooksHero>
      </div>
    </template>
  </HeroItem>
</template>

<style scoped>
.btn-primary {
  --bs-btn-padding-x: 2.8rem;
  --bs-btn-padding-y: 0.75rem;
}
</style>
