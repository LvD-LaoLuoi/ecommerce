<script setup></script>

<template>
  <div class="our-collection">
    <span class="our-collection__title">
      <img src="@/assets/icons/our-collection.png" alt="icon collection" />
      <p>Our Collection</p>
    </span>

    <div class="our-collection__product-collection">
      <div class="product 01">
        <div class="product-details">
          <img src="@/assets/images/Headphone.png" alt="image headphone" class="image-product" />
          <div class="description">
            <p class="type-product">Headphones</p>
            <p class="name-product">White Solo 2 Wireless New Year 2021</p>
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
            src="@/assets/images/Tablet_Red_Elitebook.png"
            alt="image tablet red elitebook"
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

      <div class="product 03">
        <div class="product-details">
          <img src="@/assets/images/Iphone6.png" alt="image iphone" class="image-product" />
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

      <div class="product 04">
        <div class="product-details">
          <img src="@/assets/images/Tablet_S2.png" alt="image tablet" class="image-product" />
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

      <div class="product 05">
        <div class="product-details">
          <img
            src="@/assets/images/Game_Console.png"
            alt="image game console"
            class="image-product"
          />
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

      <div class="product 06">
        <div class="product-details">
          <img src="@/assets/images/Screen.png" alt="image screen" class="image-product" />
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
  .our-collection {
    display: flex;
    flex-direction: column;
    gap: 1px;

    &__title {
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

    &__product-collection {
      display: flex;
      justify-content: start;
      align-items: center;
      gap: 1px;

      //   flex-wrap: wrap;

      .product {
        display: flex;
        flex-direction: column;
        align-items: start;
        justify-content: center;
        align-self: stretch;

        gap: 1px;
        position: relative;
        flex: 1 1 calc(100% / 6 - 1px);
        // overflow: hidden;

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
