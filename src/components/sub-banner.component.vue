<script setup></script>

<template>
  <div class="sub-banner">
    <div class="image 01">
      <img src="@/assets/images/12.png" alt="sub banner 1" />
    </div>
    <div class="image 02">
      <img src="@/assets/images/13.png" alt="sub banner 2" />
    </div>
    <div class="image 03">
      <img src="@/assets/images/14.png" alt="sub banner 3" />
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .sub-banner {
    display: flex;
    align-items: stretch;
    justify-content: space-between;
    gap: 1rem;

    .image {
      display: flex;
      flex: 1 1 calc(100% / 3 - 1rem);

      img {
        width: 100%;
      }
    }
  }
</style>
