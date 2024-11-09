<script setup></script>

<template>
  <div class="deals-section">
    <div class="deals-section__heading">
      <span class="title">
        <img src="@/assets/icons/diamon.png" alt="icon collection" />
        <p>Deals Of The Day</p>
      </span>

      <span class="times">
        <img src="@/assets/icons/oclock.png" alt="icon times" />
        <span class="digital-clock">
          <p>
            06 <span>DAYS</span> : 24 <span>HOUR</span> : 33 <span>MINE</span> : 49
            <span>SECO</span>
          </p>
        </span>
      </span>

      <span class="view-all">
        <p>VIEW ALL</p>
      </span>
    </div>

    <div class="deals-section__product-collection">
      <div class="deals-banner">
        <img src="@/assets/images/Apple_Watch_2.png" alt="deals banner" class="image" />
        <div class="detail">
          <p class="slogan">Catch Big Deals</p>
          <p class="type">ON THE SMART WATCH</p>
        </div>
      </div>

      <div class="product 01">
        <div class="product-details">
          <img
            src="@/assets/images/Apple_Screen.png"
            alt="image apple screen"
            class="image-product"
          />
          <div class="description">
            <p class="type-product">Laptops, Ultrabooks</p>
            <p class="name-product">Tablet Red EliteBook Revolve 810 G2</p>
          </div>
        </div>
        <div class="group-buttons">
          <span>
            <img src="@/assets/icons/wishlist.png" alt="icon heart" />
            <p>wishlist</p>
          </span>

          <span>
            <img src="@/assets/icons/orders.png" alt="icon compare" class="icon-compare" />
            <p>compare</p>
          </span>
        </div>
        <span class="shopping-cart">
          <img src="@/assets/icons/shop-cart.png" alt="icon cart" />
        </span>
      </div>

      <div class="product 02">
        <div class="product-details">
          <img
            src="@/assets/images/appple_watch.png"
            alt="image apple watch"
            class="image-product"
          />
          <div class="description">
            <p class="type-product">Phone, Iphone</p>
            <p class="name-product">Iphone 6 64GB Space Grey New</p>
          </div>
        </div>
        <div class="group-buttons">
          <span>
            <img src="@/assets/icons/wishlist.png" alt="icon heart" />
            <p>wishlist</p>
          </span>

          <span>
            <img src="@/assets/icons/orders.png" alt="icon compare" class="icon-compare" />
            <p>compare</p>
          </span>
        </div>
        <span class="shopping-cart">
          <img src="@/assets/icons/shop-cart.png" alt="icon cart" />
        </span>
      </div>

      <div class="product 03">
        <div class="product-details">
          <img src="@/assets/images/Webcame.png" alt="image webcame" class="image-product" />
          <div class="description">
            <p class="type-product">Tablets</p>
            <p class="name-product">White Tablet S2 WIFi 62GB Lite Internet</p>
          </div>
        </div>
        <div class="group-buttons">
          <span>
            <img src="@/assets/icons/wishlist.png" alt="icon heart" />
            <p>wishlist</p>
          </span>

          <span>
            <img src="@/assets/icons/orders.png" alt="icon compare" class="icon-compare" />
            <p>compare</p>
          </span>
        </div>
        <span class="shopping-cart">
          <img src="@/assets/icons/shop-cart.png" alt="icon cart" />
        </span>
      </div>

      <div class="product 04">
        <div class="product-details">
          <img src="@/assets/images/Chair.png" alt="image chair" class="image-product" />
          <div class="description">
            <p class="type-product">Game Consoles</p>
            <p class="name-product">Game Console Controller + USB 3.0 Cable</p>
          </div>
        </div>
        <div class="group-buttons">
          <span>
            <img src="@/assets/icons/wishlist.png" alt="icon heart" />
            <p>wishlist</p>
          </span>

          <span>
            <img src="@/assets/icons/orders.png" alt="icon compare" class="icon-compare" />
            <p>compare</p>
          </span>
        </div>
        <span class="shopping-cart">
          <img src="@/assets/icons/shop-cart.png" alt="icon cart" />
        </span>
      </div>

      <div class="product 05">
        <div class="product-details">
          <img src="@/assets/images/Headphone_2.png" alt="image headphone" class="image-product" />
          <div class="description">
            <p class="type-product">Screens, TVs</p>
            <p class="name-product">TV Smart LED HD Android TV</p>
          </div>
        </div>
        <div class="group-buttons">
          <span>
            <img src="@/assets/icons/wishlist.png" alt="icon heart" />
            <p>wishlist</p>
          </span>

          <span>
            <img src="@/assets/icons/orders.png" alt="icon compare" class="icon-compare" />
            <p>compare</p>
          </span>
        </div>
        <span class="shopping-cart">
          <img src="@/assets/icons/shop-cart.png" alt="icon cart" />
        </span>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .deals-section {
    display: flex;
    flex-direction: column;
    gap: 1px;

    &__heading {
      display: flex;
      align-items: center;
      justify-content: space-between;
      background-color: $color-bg-primary;

      & > * {
        display: flex;
        align-items: center;
        align-self: stretch;

        padding: 1.8rem 1.2rem;
      }

      .title {
        gap: 0.5rem;

        img {
          width: 2.4rem;
        }

        p {
          font-size: 1.8rem;
          font-weight: 700;
          color: $color-primary-dark;
        }
      }

      .times {
        gap: 1rem;

        img {
          width: 2.2rem;
        }

        p {
          font-size: 1.8rem;
          font-weight: 700;
          color: $color-primary-dark;
        }

        span {
          font-size: 1.4rem;
          font-weight: 500;

          padding-right: 2rem;
        }
      }

      .view-all {
        p {
          font-size: 1.6rem;
          font-weight: 600;
          color: $color-accent-2;
        }
      }
    }

    &__product-collection {
      display: flex;
      justify-content: start;
      align-items: center;
      gap: 1px;

      //   flex-wrap: wrap;

      .deals-banner {
        display: flex;
        flex-direction: column;
        align-self: stretch;
        flex: 1 1 calc(100% / 6 - 1px);
        width: 100%;

        background-image: linear-gradient(0deg, $color-accent-7 35%, $color-accent-8);
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;

        position: relative;

        .image {
          position: absolute;
          top: 32%;
          left: 50%;
          transform: translate(-50%, -50%);
        }

        .detail {
          position: absolute;
          left: 14%;
          bottom: 16%;

          .slogan {
            font-size: 1.4rem;
            font-weight: 500;
            color: $color-primary-light-3;
            letter-spacing: 1px;
          }

          .type {
            font-size: 2.2rem;
            font-weight: 600;
            color: $color-secondary;
            letter-spacing: 1.2px;
          }
        }
      }

      .product {
        display: flex;
        flex-direction: column;
        align-items: start;
        justify-content: center;
        align-self: stretch;

        gap: 1px;
        position: relative;
        flex: 1 1 calc(100% / 6 - 1px);

        .product-details {
          flex: 1 0 auto;
          align-self: stretch;

          display: flex;
          flex-direction: column;
          align-items: start;

          position: relative;

          .image-product {
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
          }

          .description {
            display: flex;
            flex-direction: column;
            align-items: start;

            width: 100%;

            padding: 1rem 1.8rem;
            background-color: $color-bg-primary;
            overflow: hidden;

            .type-product {
              font-size: 1.2rem;
              font-weight: 500;
              color: $color-primary-light-2;
            }

            .name-product {
              align-self: stretch;
              padding: 0.8rem 0;
              min-height: 6.8rem;

              font-size: 1.6rem;
              font-weight: 700;

              overflow: hidden; /* Hide overflowing text */
              display: -webkit-box; /* Enable flexbox layout */
              -webkit-box-orient: vertical; /* Stack content vertically */
              line-clamp: 2;
              -webkit-line-clamp: 2; /* Limit to 2 lines */
              text-overflow: ellipsis;

              line-height: 1.65;
            }
          }
        }

        .product-details::after {
          content: '';
          width: 100%;
          height: 3.6rem;
          background-color: $color-bg-primary;
          visibility: visible;
        }

        .group-buttons {
          display: flex;
          align-items: center;
          justify-content: center;
          align-self: stretch;

          position: absolute;
          bottom: 0;
          left: 0;
          gap: 1px;

          width: 100%;
          visibility: hidden;

          img {
            width: 1.8rem;
          }

          p {
            font-size: 1.2rem;
            font-weight: 500;
            color: $color-primary-light-2;
          }

          span {
            display: flex;
            align-items: center;
            justify-content: center;
            flex: 1 1 calc(50% - 1px);

            width: 100%;
            gap: 0.5rem;
            padding: 0.8rem 1.2rem;
            background-color: $color-bg-primary;
          }

          .icon-compare {
            filter: brightness(0) saturate(100%) invert(34%) sepia(12%) saturate(3%)
              hue-rotate(358deg) brightness(92%) contrast(91%);
          }
        }

        .shopping-cart {
          display: flex;
          align-items: center;
          justify-content: center;

          position: absolute;
          top: 2rem;
          left: 1.5rem;

          img {
            width: 3.6rem;
            filter: brightness(0) saturate(100%) invert(95%) sepia(92%) saturate(18%)
              hue-rotate(183deg) brightness(116%) contrast(87%);
            border-radius: 50%;
            border: 0.5px solid $color-primary-light-3;
          }
        }

        &:hover .group-buttons {
          visibility: visible;
        }

        &:hover .product-details::after {
          visibility: hidden;
        }

        &:hover .shopping-cart {
          img {
            filter: brightness(0) saturate(100%) invert(36%) sepia(61%) saturate(3925%)
              hue-rotate(346deg) brightness(97%) contrast(108%);

            border: 0.5px solid $color-accent-2;
          }
        }
      }
    }
  }
</style>
