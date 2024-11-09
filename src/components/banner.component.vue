<script setup></script>

<template>
  <div class="banner-section">
    <div class="banner-section__departments">
      <span>
        <img src="@/assets/icons/computer.png" alt="icon computer" />
        <p>Computers & Accessories</p>
      </span>
      <span>
        <img src="@/assets/icons/camera.png" alt="icon camera" />
        <p>Cameras, Audio & Video</p>
      </span>
      <span>
        <img src="@/assets/icons/mobiles.png" alt="icon mobiles" />
        <p>Mobiles & Tablets</p>
      </span>
      <span>
        <img src="@/assets/icons/movies.png" alt="icon movies" />
        <p>Movies, Music & Video Games</p>
      </span>
      <span>
        <img src="@/assets/icons/tv.png" alt="icon tv" />
        <p>TV & Audio</p>
      </span>
      <span>
        <img src="@/assets/icons/watches.png" alt="icon watches" />
        <p>Watches & Eyewear</p>
      </span>
      <span>
        <img src="@/assets/icons/car.png" alt="icon bicycle" />
        <p>Car, Motorbike & Industrial</p>
      </span>
      <span>
        <img src="@/assets/icons/accessories.png" alt="icon accessories" />
        <p>Accessories</p>
      </span>
      <span>
        <img src="@/assets/icons/value.png" alt="icon value" />
        <p>Value of the Day</p>
      </span>
      <span>
        <img src="@/assets/icons/top.png" alt="icon top" />
        <p>Top 100 Offers</p>
      </span>
    </div>
    <div class="banner-section__pictures">
      <div class="messages">
        <span>NEW ARRIVALS</span>
        <span>FEATURED BRANDS</span>
        <span>TRENDING STYLES</span>
        <span>GIFT CARDS</span>
      </div>
      <div class="details">
        <div class="description">
          <h2>New Virtual Reality Headset</h2>
          <p>Compengly streamline cooperative theme awesome synergistic process.</p>
          <button>START BUYING</button>
        </div>
        <div class="dots">
          <img src="@/assets/icons/dot.svg" alt="dot 01" />
          <img src="@/assets/icons/dot.svg" alt="dot 02" />
          <img src="@/assets/icons/dot.svg" alt="dot 03" />
          <img src="@/assets/icons/dot-fill.svg" alt="dot 04" />
          <img src="@/assets/icons/dot.svg" alt="dot 05" />
          <img src="@/assets/icons/dot.svg" alt="dot 06" />
        </div>
      </div>
    </div>
    <div class="banner-section__services">
      <span>
        <img src="@/assets/icons/services.png" alt="icon services" />
        <p>24/7 Services</p>
      </span>

      <span>
        <img src="@/assets/icons/multiple-language.png" alt="icon multi" />
        <p>Multi language</p>
      </span>

      <span>
        <img src="@/assets/icons/protection.png" alt="icon protection" />
        <p>Protection</p>
      </span>

      <span>
        <img src="@/assets/icons/payments.png" alt="icon payments" />
        <p>Payments</p>
      </span>
    </div>
    <div class="banner-section__new-products">
      <div class="product 01">
        <div class="info-details">
          <p class="details">Catch Big Deals On The Smart Watch</p>
          <span>
            <p class="show">SHOW NOW</p>
            <span class="arrow-right">
              <img src="@/assets/icons/arrow-right.svg" alt="icon arrow-right" />
            </span>
          </span>
        </div>
        <img src="@/assets/images/Appple_Watch.png" alt="picture apple" class="image-product" />
      </div>

      <div class="product 02">
        <div class="info-details">
          <p class="details">Catch Big Deals On The Computer</p>
          <span>
            <p class="show">SHOW NOW</p>
            <span class="arrow-right">
              <img src="@/assets/icons/arrow-right.svg" alt="icon arrow-right" />
            </span>
          </span>
        </div>
        <img src="@/assets/images/Apple_Screen.png" alt="picture screen" class="image-product" />
      </div>

      <div class="product 03">
        <div class="info-details">
          <p class="details">Shop The Best Hottest Products</p>
          <span>
            <p class="show">SHOW NOW</p>
            <span class="arrow-right">
              <img src="@/assets/icons/arrow-right.svg" alt="icon arrow-right" />
            </span>
          </span>
        </div>
        <img src="@/assets/images/Chair.png" alt="picture screen" class="image-product" />
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .banner-section {
    display: flex;
    gap: 1rem;
    align-items: center;
    flex-wrap: wrap;

    & > * {
      display: flex;
      border: none;
    }

    &__departments {
      flex-direction: column;
      align-items: start;
      align-self: stretch;
      flex: 1 1 18%;
      background-color: $color-bg-primary;

      & > :not(span:last-child) {
        border-bottom: 1px inset $color-primary-light-3;
      }

      span {
        display: flex;
        gap: 0.5rem;
        cursor: pointer;

        width: 100%;
        padding: 1.8rem 1.2rem;
      }

      img {
        width: 1.6rem;
      }

      p {
        width: 100%;
        font-size: 1.3rem;
        font-weight: 500;
      }

      span:hover p {
        color: $color-accent-2;
      }
    }

    &__pictures {
      flex-direction: column;
      align-self: stretch;
      flex: 1 1 calc(82% - 1rem);
      width: 100%;

      .messages {
        display: flex;
        justify-content: space-between;
        padding: 1.8rem 6.4rem;

        font-size: 1.3rem;
        font-weight: 600;
        color: $color-secondary;
        background-color: $color-accent-2;
      }

      .details {
        position: relative;
        width: 100%;
        height: 100%;
        color: $color-secondary;
        background-image: linear-gradient(
            to right,
            $color-accent-3 10%,
            $color-accent-3 20%,
            transparent 30%
          ),
          url('@/assets/images/banner_1.png');
        background-size: cover;
        background-repeat: no-repeat;
        background-position: right bottom;

        .description {
          position: absolute;
          top: 50%;
          left: 11rem;
          transform: translateY(-50%);

          width: 40%;

          h2 {
            font-size: 6rem;
          }

          p {
            font-size: 2.4rem;
          }

          button {
            font-size: 1.6rem;
            font-weight: 600;
            padding: 2rem 3.7rem;
            margin-top: 3rem;

            color: $color-accent-3;
            background-color: $color-secondary;
          }
        }

        .dots {
          position: absolute;
          left: 50%;
          bottom: 2.4rem;
          transform: translateX(-50%);

          img {
            width: 2.4rem;
            filter: brightness(0) saturate(100%) invert(100%) sepia(100%) saturate(0%)
              hue-rotate(135deg) brightness(108%) contrast(104%);
          }
        }
      }
    }

    &__services {
      justify-content: start;
      align-items: center;
      flex-wrap: wrap;

      gap: 1px;
      flex: 1 1 18%;

      span {
        display: flex;
        align-items: center;
        flex-direction: column;
        flex: 1 1 calc(50% - 1px);

        padding: 4rem 2.2rem;
        background-color: $color-secondary;
      }

      img {
        max-width: 3.4rem;
      }

      p {
        font-size: 1.2rem;
        font-weight: 500;
      }
    }

    &__new-products {
      align-self: stretch;
      gap: 1rem;
      flex-basis: calc(82% - 1rem);
      width: 100%;

      .product {
        display: flex;
        justify-content: start;
        align-items: center;
        flex: 1 1 calc(100% / 3);
        background-color: $color-bg-primary;

        .info-details {
          flex: 1 1 50%;
          margin-left: 2.2rem;

          .details {
            font-size: 1.8rem;
            font-weight: 500;
            margin-bottom: 2.2rem;
          }

          .show {
            font-size: 1.6rem;
            font-weight: 700;
            color: $color-accent-2;
          }

          .arrow-right {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 0.4rem;

            margin-left: 0.4rem;
            border-radius: 50%;
            background-color: $color-accent-2;
          }

          span {
            display: flex;
            justify-content: start;
            align-items: center;
          }

          img {
            width: 1rem;
            font-weight: 600;
            filter: brightness(0) saturate(100%) invert(100%) sepia(100%) saturate(0%)
              hue-rotate(135deg) brightness(108%) contrast(104%);
          }
        }

        .image-product {
          flex: 0 1 50%;
          max-width: 100%;
        }
      }
    }
  }
</style>
