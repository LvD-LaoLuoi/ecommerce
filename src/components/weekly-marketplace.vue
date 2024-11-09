<script setup></script>

<template>
  <div class="arrivals-global">
    <div class="new-arrivals">
      <div class="heading">
        <img src="@/assets/icons/weekly-deals.png" alt=" icon weekly deals" />
        <p>Weekly Deals</p>
      </div>
      <div class="new-products">
        <div class="banner arrivals-banner">
          <h3>From 30% Off</h3>
          <div class="deals-end">
            <p>Deals End In:</p>
            <div class="number-end">
              <span>07</span>
              <span>24</span>
              <span>36</span>
              <span>33</span>
            </div>
          </div>
          <a href="#">view more &gt;&gt;</a>
        </div>
        <div class="product 01">
          <img src="@/assets/images/26.png" alt="image chair" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 120.00</p>
          </span>
        </div>

        <div class="product 02">
          <img src="@/assets/images/27.png" alt="image iphone" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 160.00</p>
          </span>
        </div>

        <div class="product 03">
          <img src="@/assets/images/28.png" alt="image chair 2" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 230.00</p>
          </span>
        </div>
      </div>
    </div>
    <div class="global-original">
      <div class="heading">
        <img src="@/assets/icons/small-commodities.png" alt=" Small Marketplace" />
        <p>Small Commodities Marketplace</p>
      </div>
      <div class="new-products">
        <div class="banner original-banner">
          <h3>A Wide Range Of Selected Goods With Fast Free Shipping</h3>
          <a href="#">view more &gt;&gt;</a>
        </div>

        <div class="product 01">
          <img src="@/assets/images/30.png" alt="Product 30" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 120.00</p>
          </span>
        </div>

        <div class="product 02">
          <img src="@/assets/images/31.png" alt="Product 31" />
          <span>
            <p class="name">Tablet EliteBook</p>
            <p class="price">$ 160.00</p>
          </span>
        </div>

        <div class="product 03">
          <img src="@/assets/images/32.png" alt="Product 32" />
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
    align-items: stretch;
    gap: 2rem;

    width: 100%;

    .new-arrivals,
    .global-original {
      display: flex;
      flex-direction: column;
      justify-content: stretch;
      align-items: stretch;
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
        justify-content: stretch;
        align-items: center;
        gap: 1rem;

        height: 100%;
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

        .banner {
          display: flex;
          flex-direction: column;
          align-items: stretch;
          height: 100%;

          flex: 1 1 40%;
          padding: 3.2rem 2.4rem;
          background-size: cover;

          h3 {
            font-size: 1.8rem;
            font-weight: 700;
            color: $color-secondary;
          }

          a {
            font-size: 1.3rem;
            font-weight: 500;
            color: $color-secondary;
          }
        }

        .arrivals-banner {
          gap: 1rem;
          background-image: url('@/assets/images/25.png');
          background-size: cover;

          .deals-end {
            display: flex;
            flex-direction: column;
            align-items: start;
            gap: 0.5rem;

            p {
              font-size: 1.2rem;
              font-weight: 500;
              color: $color-secondary;
            }

            .number-end {
              display: flex;
              align-items: center;
              justify-content: start;
              gap: 0.4rem;

              span {
                font-size: 1.2rem;
                font-weight: 500;
                padding: 0.6rem 0.8rem;

                border-radius: 2px;
                color: $color-primary-dark;
                background-color: $color-secondary;
              }
            }
          }
        }

        .original-banner {
          gap: 3rem;
          background-image: url('@/assets/images/29.png');
          background-size: cover;
        }
      }
    }
  }
</style>
