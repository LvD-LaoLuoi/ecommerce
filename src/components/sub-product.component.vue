<script setup></script>

<template>
  <div class="sub-product">
    <div class="heading">
      <img src="@/assets/icons/diamon.png" alt="icon diamon" />
      <p>Our New Products</p>
    </div>

    <div class="list-product">
      <div class="banner">
        <div class="banner__info">
          <p>Diversified Procurement Best Solutions</p>
          <button>Source Now</button>
        </div>
        <img src="@/assets/images/15.png" alt="15" class="banner__image" />
      </div>

      <div class="all-product">
        <div class="product 01">
          <img src="@/assets/images/16.png" alt="16" class="image" />
          <div class="info">
            <p class="slogan-product">Catch Big Deals The Computer</p>
            <span class="show-now">
              <p class="show">SHOW NOW</p>
              <span class="icon">
                <img src="@/assets/icons/arrow-right.svg" alt="icon arrow-right" />
              </span>
            </span>
          </div>
        </div>

        <div class="product 02">
          <img src="@/assets/images/17.png" alt="17" class="image" />
          <div class="info">
            <p class="slogan-product">Catch Big Deals The Chair</p>
            <span class="show-now">
              <p class="show">SHOW NOW</p>
              <span class="icon">
                <img src="@/assets/icons/arrow-right.svg" alt="icon arrow-right" />
              </span>
            </span>
          </div>
        </div>

        <div class="product 03">
          <img src="@/assets/images/18.png" alt="18" class="image" />
          <div class="info">
            <p class="slogan-product">Catch Big Deals The Apple Watch</p>
            <span class="show-now">
              <p class="show">SHOW NOW</p>
              <span class="icon">
                <img src="@/assets/icons/arrow-right.svg" alt="icon arrow-right" />
              </span>
            </span>
          </div>
        </div>

        <div class="product 04">
          <img src="@/assets/images/19.png" alt="19" class="image" />
          <div class="info">
            <p class="slogan-product">Catch Big Deals The Camera</p>
            <span class="show-now">
              <p class="show">SHOW NOW</p>
              <span class="icon">
                <img src="@/assets/icons/arrow-right.svg" alt="icon arrow-right" />
              </span>
            </span>
          </div>
        </div>

        <div class="product 05">
          <img src="@/assets/images/20.png" alt="20" class="image" />
          <div class="info">
            <p class="slogan-product">Catch Big Deals The Headphones</p>
            <span class="show-now">
              <p class="show">SHOW NOW</p>
              <span class="icon">
                <img src="@/assets/icons/arrow-right.svg" alt="icon arrow-right" />
              </span>
            </span>
          </div>
        </div>

        <div class="product 06">
          <img src="@/assets/images/21.png" alt="21" class="image" />
          <div class="info">
            <p class="slogan-product">Catch Big Deals The Computer</p>
            <span class="show-now">
              <p class="show">SHOW NOW</p>
              <span class="icon">
                <img src="@/assets/icons/arrow-right.svg" alt="icon arrow-right" />
              </span>
            </span>
          </div>
        </div>

        <div class="product 07">
          <img src="@/assets/images/22.png" alt="22" class="image" />
          <div class="info">
            <p class="slogan-product">Catch Big Deals The Mac Book</p>
            <span class="show-now">
              <p class="show">SHOW NOW</p>
              <span class="icon">
                <img src="@/assets/icons/arrow-right.svg" alt="icon arrow-right" />
              </span>
            </span>
          </div>
        </div>

        <div class="product 08">
          <img src="@/assets/images/23.png" alt="23" class="image" />
          <div class="info">
            <p class="slogan-product">Catch Big Deals The TV</p>
            <span class="show-now">
              <p class="show">SHOW NOW</p>
              <span class="icon">
                <img src="@/assets/icons/arrow-right.svg" alt="icon arrow-right" />
              </span>
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .sub-product {
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 1px;

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

    .list-product {
      display: flex;
      justify-content: start;
      align-items: stretch;
      gap: 1px;

      .banner {
        display: flex;
        align-items: stretch;
        justify-content: start;
        flex: 1 1 calc(46% - 1px);

        position: relative;
        background-color: $color-bg-primary;

        &__image {
          width: 100%;
          padding-left: 14rem;
        }

        &__info {
          display: flex;
          flex-direction: column;
          align-items: start;
          gap: 2rem;

          position: absolute;
          top: 0;
          right: 32%;

          width: 66%;
          padding: 1.8rem 1.2rem;

          p {
            font-size: 1.8rem;
            font-weight: 500;
            letter-spacing: 1.2px;
            line-height: 1.4;
          }

          button {
            display: flex;
            align-items: center;
            padding: 0.8rem 1.6rem;

            font-weight: 500;
            color: $color-secondary;
            background-color: $color-accent-2;

            border: none;
            box-shadow: 0 4px 10px $color-accent-2;
          }
        }
      }

      .all-product {
        display: flex;
        justify-content: start;
        align-items: stretch;
        flex-wrap: wrap;
        gap: 1px;

        width: 100%;

        .product {
          display: flex;
          flex-direction: column;
          align-items: stretch;
          flex: 1 1 calc(100% / 4 - 1px);

          width: 100%;
          position: relative;
          background-color: $color-bg-primary;

          .image {
            width: 45%;
            position: absolute;
            right: 1.4rem;
            bottom: 0;
            z-index: 2;
          }

          .info {
            display: flex;
            flex-direction: column;
            align-items: start;

            width: 100%;
            gap: 1rem;
            padding: 2.4rem 1.8rem;
            z-index: 3;

            .slogan-product {
              font-size: 1.3rem;
              font-weight: 500;
              letter-spacing: 1.2px;
              line-height: 1.4;

              min-height: 4rem;
            }

            .show-now {
              display: flex;
              align-items: center;
              gap: 0.5rem;

              .show {
                font-size: 1rem;
                font-weight: 800;
                color: $color-primary-dark;
              }

              .icon {
                display: flex;
                align-items: center;

                padding: 0.2rem;
                border-radius: 50%;
                background-color: $color-primary-dark;

                img {
                  width: 0.8rem;
                  filter: brightness(0) saturate(100%) invert(100%) sepia(52%) saturate(2%)
                    hue-rotate(49deg) brightness(105%) contrast(101%);
                }
              }
            }
          }
        }
      }
    }
  }
</style>
