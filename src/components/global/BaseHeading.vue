<script setup></script>

<template>
  <div class="py-2">
    <span class="text-primary fw-bold text-uppercase">
      <slot name="subheading-text"></slot>
    </span>
  </div>
  <div>
    <h2 class="fw-bold text-secondary">
      <slot name="heading-text"></slot>
    </h2>
  </div>
</template>
