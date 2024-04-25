<script setup>
import Container from "@/components/Container.vue";
</script>

<template>
  <Container>
    <div class="py-3">
      <div>
        <div class="py-2">
          <span class="text-primary fw-bold text-uppercase">
            <slot name="subheading-review"></slot>
          </span>
        </div>
        <div>
          <h2 class="fw-bold text-secondary">
            <slot name="heading-review"></slot>
          </h2>
        </div>
        <div class="row g-5 py-5">
          <div class="col-md-4">
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
                  <slot name="review-left-desc"></slot>
                </p>
                <h5 class="card-title text-primary">
                  <slot name="review-left-author"></slot>
                </h5>
                <span class="text-secondary">
                  <slot name="review-left-occupation"></slot>
                </span>
              </div>
            </div>
          </div>
          <div class="col-md-4">
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
                  <slot name="review-center-desc"></slot>
                </p>
                <h5 class="card-title text-primary">
                  <slot name="review-center-author"></slot>
                </h5>
                <span class="text-secondary">
                  <slot name="review-center-occupation"></slot>
                </span>
              </div>
            </div>
          </div>
          <div class="col-md-4">
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
                  <slot name="review-right-desc"></slot>
                </p>
                <h5 class="card-title text-primary">
                  <slot name="review-right-author"></slot>
                </h5>
                <span class="text-secondary">
                  <slot name="review-right-occupation"></slot>
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </Container>
</template>
