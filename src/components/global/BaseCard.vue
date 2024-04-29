<template>
  <div class="card shadow-lg border-0 p-3">
    <div class="text-center py-2">
      <img
        src="https://picsum.photos/200/300?image=0"
        class="rounded-circle"
        alt="#"
        width="100"
      />
    </div>
    <div class="card-body text-center">
      <p class="card-text">
        <slot name="review-desc"></slot>
      </p>
      <h5 class="card-title text-primary">
        <slot name="review-author"></slot>
      </h5>
      <span class="text-secondary">
        <slot name="review-occupation"></slot>
      </span>
    </div>
  </div>
</template>
