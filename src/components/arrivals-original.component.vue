<script setup></script>

<template>
  <div class="arrivals-global">
    <div class="new-arrivals">
      <div class="heading">
        <img src="@/assets/icons/gift.png" alt=" new arrivals" />
        <p>New Arrivals</p>
      </div>
      <div class="new-products">
        <div class="product 01">
          <img src="@/assets/images/Iphone_1.png" alt="phone 1" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 140.00</p>
          </span>
        </div>

        <div class="product 02">
          <img src="@/assets/images/Iphone_2.png" alt="phone 2" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 120.00</p>
          </span>
        </div>

        <div class="product 03">
          <img src="@/assets/images/Iphone_3.png" alt="phone 3" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 120.00</p>
          </span>
        </div>

        <div class="product 04">
          <img src="@/assets/images/Iphone_4.png" alt="phone 4" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 160.00</p>
          </span>
        </div>

        <div class="product 05">
          <img src="@/assets/images/Iphone_5.png" alt="phone 5" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 230.00</p>
          </span>
        </div>
      </div>
    </div>
    <div class="global-original">
      <div class="heading">
        <img src="@/assets/icons/global.png" alt=" Global Original" />
        <p>Global Original Sources</p>
      </div>
      <div class="new-products">
        <div class="product 01">
          <img src="@/assets/images/1.png" alt="Product 1" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 140.00</p>
          </span>
        </div>

        <div class="product 02">
          <img src="@/assets/images/2.png" alt="Product 2" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 120.00</p>
          </span>
        </div>

        <div class="product 03">
          <img src="@/assets/images/3.png" alt="Product 3" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 120.00</p>
          </span>
        </div>

        <div class="product 04">
          <img src="@/assets/images/4.png" alt="Product 4" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 160.00</p>
          </span>
        </div>

        <div class="product 05">
          <img src="@/assets/images/5.png" alt="Product 5" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 230.00</p>
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .arrivals-global {
    display: flex;
    align-items: center;
    gap: 2rem;

    width: 100%;

    .new-arrivals,
    .global-original {
      display: flex;
      flex-direction: column;
      justify-content: center;
      gap: 1px;

      flex: 1 1 calc(50% - 2rem);

      .heading {
        display: flex;
        align-items: center;
        gap: 0.5rem;

        padding: 1.8rem 1.2rem;
        background-color: $color-bg-primary;

        img {
          width: 2.4rem;
        }

        p {
          font-size: 1.8rem;
          font-weight: 700;
          color: $color-primary-dark;
        }
      }

      .new-products {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 1rem;

        padding: 1rem;
        background-color: $color-bg-primary;

        .product {
          display: flex;
          flex-direction: column;
          align-items: center;
          gap: 1rem;

          img {
            width: 100%;
          }

          span {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 0.5rem;

            p {
              font-size: 1.2rem;
              font-weight: 500;
            }
          }
        }
      }
    }
  }
</style>
