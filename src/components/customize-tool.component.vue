<script setup></script>

<template>
  <div class="customize-tool">
    <div class="tool 01">
      <img src="@/assets/icons/high-quality.png" alt="tool 1" />
      <h3>High Quality Selection</h3>
      <p>
        Conveniently customize and recapitalize focused interactions without affecting global
        settings
      </p>
    </div>

    <div class="tool 02">
      <img src="@/assets/icons/affordable-prices.png" alt="tool 2" />
      <h3>Affordable Prices</h3>
      <p>
        Conveniently customize and recapitalize focused interactions without affecting global
        settings
      </p>
    </div>

    <div class="tool 03">
      <img src="@/assets/icons/expresss-shipping.png" alt="tool 3" />
      <h3>Express Shipping</h3>
      <p>
        Conveniently customize and recapitalize focused interactions without affecting global
        settings
      </p>
    </div>

    <div class="tool 04">
      <img src="@/assets/icons/worry-free.png" alt="tool 4" />
      <h3>Worry-Free After-Sales</h3>
      <p>
        Conveniently customize and recapitalize focused interactions without affecting global
        settings
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .customize-tool {
    display: flex;
    justify-content: stretch;
    gap: 1rem;

    .tool {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 1.2rem;

      padding: 3.2rem 2.2rem;
      background-color: $color-bg-primary;

      img {
        width: 4rem;
      }

      h3 {
        font-size: 1.6rem;
        font-weight: 600;
        color: $color-primary-dark;
      }

      p {
        font-size: 1.2rem;
        font-weight: 500;
        text-align: center;
        line-height: 1.6;
      }
    }
  }
</style>
