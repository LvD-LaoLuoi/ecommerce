<script setup></script>

<template>
  <div class="sub-footer">
    <div class="payment-method">
      <span class="icon-sub">
        <img src="@/assets/icons/pay-daily.png" alt="visa" />
        <p>Pay with:</p>
      </span>
      <span>
        <img src="@/assets/icons/master-card.png" alt="mastercard" />
        <img src="@/assets/icons/visa.png" alt="visa" />
        <img src="@/assets/icons/maestro.png" alt="maestro" />
        <img src="@/assets/icons/paypal.png" alt="paypal" />
        <img src="@/assets/icons/discovery.png" alt="discovery" />
        <img src="@/assets/icons/jcb.png" alt="jcb" />
        <img src="@/assets/icons/skrill.png" alt=" skrill" />
      </span>
    </div>
    <div class="visitors-view">
      <span class="icon-sub">
        <img src="@/assets/icons/pay-daily.png" alt="visa" />
        <p>Daily Visitors:</p>
      </span>
      <span class="number-visitors">
        <p>3</p>
        <p>234</p>
        <p>567</p>
        <p>890+</p>
      </span>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .sub-footer {
    display: flex;
    align-items: center;

    width: 100%;
    padding: 2rem 20rem;
    background-color: $color-bg-primary;
    border-bottom: 0.4px inset $color-primary-light-3;

    .icon-sub {
      display: flex;
      align-items: center;
      gap: 0.8rem;

      img {
        width: 3.8rem;
      }

      p {
        font-size: 1.2rem;
        font-weight: 500;
      }
    }

    .payment-method {
      display: flex;
      align-items: center;
      gap: 1.6rem;

      flex: 1 1 auto;

      span {
        display: flex;
        align-items: center;
        gap: 0.8rem;

        img {
          width: 3.8rem;
        }
      }
    }

    .visitors-view {
      display: flex;
      align-items: center;
      gap: 1.6rem;

      flex: 1 1 auto;

      .number-visitors {
        display: flex;
        align-items: center;
        gap: 0.4rem;

        p {
          font-size: 1.8rem;
          font-weight: 700;
          color: $color-primary-dark;
        }
      }
    }
  }
</style>
