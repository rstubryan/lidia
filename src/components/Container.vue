<script setup>
import BackgroundCover from "./icons/CoverBackground.vue";
</script>

<template>
  <div class="my-5">
    <div class="container">
      <div class="container-fluid">
        <div class="d-none d-lg-block z-n1 position-absolute top-0 start-50">
          <BackgroundCover />
        </div>
        <slot></slot>
      </div>
    </div>
  </div>
</template>
