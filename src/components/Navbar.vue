<script setup>
import { ref } from "vue";
import Container from "@/components/Container.vue";
import IconLogo from "@/components/icons/IconLogo.vue";

const appName = ref("Lidia");
const navList = ref([
  { text: "Feature", url: "/" },
  { text: "Service", url: "/service" },
  { text: "Review", url: "/review" },
  { text: "Location", url: "/location" },
]);
</script>

<template>
  <Container>
    <nav class="navbar navbar-expand-lg">
      <div class="container-fluid">
        <div class="d-flex m-0 align-items-center gap-2">
          <IconLogo></IconLogo>
          <a class="navbar-brand fw-bold" href="#">{{ appName }}</a>
        </div>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <div class="me-auto">
            <ul class="navbar-nav ms-0 ms-lg-5 mb-2 mb-lg-0 d-flex gap-3">
              <li v-for="item in navList" :key="item.text" class="nav-item">
                <a :href="item.url" class="nav-link">{{ item.text }}</a>
              </li>
            </ul>
          </div>
          <div>
            <button class="btn btn-light fw-bold" type="submit">Login</button>
          </div>
        </div>
      </div>
    </nav>
  </Container>
</template>

<style scoped>
.btn-light {
  --bs-btn-padding-x: 2.5rem;
}
</style>
