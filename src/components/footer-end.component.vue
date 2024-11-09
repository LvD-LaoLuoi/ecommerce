<script setup></script>

<template>
  <div class="footer-end">
    <div class="nav-footer">
      <div class="col 01">
        <h3 class="heading">All Technology</h3>
        <ul>
          <li><a href="#">Tablet Accessories</a></li>
          <li><a href="#">Accessories</a></li>
          <li><a href="#">Power Banks</a></li>
          <li><a href="#">Phone Cases</a></li>
          <li><a href="#">Mobiles</a></li>
          <li><a href="#">Tablets</a></li>
        </ul>
      </div>

      <div class="col 02">
        <h3 class="heading">Women's Fashion</h3>
        <ul>
          <li><a href="#">Fabulous Floral Up to 70%</a></li>
          <li><a href="#">Cheongsam</a></li>
          <li><a href="#">Back to Black</a></li>
          <li><a href="#">5 Stars Rating</a></li>
          <li><a href="#">Dresses</a></li>
          <li><a href="#">Tops</a></li>
        </ul>
      </div>

      <div class="col 03">
        <h3 class="heading">Home And Living</h3>
        <ul>
          <li><a href="#">Air Conditioners</a></li>
          <li><a href="#">Air Purifiers</a></li>
          <li><a href="#">Fans</a></li>
          <li><a href="#">Freezers</a></li>
          <li><a href="#">Washing Machines</a></li>
          <li><a href="#">Refrigerators</a></li>
        </ul>
      </div>

      <div class="col 04">
        <h3 class="heading">Health And Beauty</h3>
        <ul>
          <li><a href="#">Treatments & Serum</a></li>
          <li><a href="#">Moisturizers & Sunscreen</a></li>
          <li><a href="#">Toners</a></li>
          <li><a href="#">Face Cleansers</a></li>
          <li><a href="#">Face Masks</a></li>
          <li><a href="#">Gift Cards</a></li>
        </ul>
      </div>

      <div class="col 05">
        <h3 class="heading">Baby And Toddler</h3>
        <ul>
          <li><a href="#">Diapering & Potty</a></li>
          <li><a href="#">Disposable Diapers</a></li>
          <li><a href="#">Diaper Bags</a></li>
          <li><a href="#">Cloth Diapers</a></li>
          <li><a href="#">Baby Gear</a></li>
          <li><a href="#">Support Baby</a></li>
        </ul>
      </div>

      <div class="col 06">
        <h3 class="heading">Sports And Outdoors</h3>
        <ul>
          <li><a href="#">Exercise & Fitness</a></li>
          <li><a href="#">Cardio & Aerobics</a></li>
          <li><a href="#">Strength Training</a></li>
          <li><a href="#">Fitness Accessories</a></li>
          <li><a href="#">Weight Loss</a></li>
          <li><a href="#">Yoga</a></li>
        </ul>
      </div>
    </div>
    <div class="description-footer">
      <div class="person-design">
        <p>All Rights Reserved. Designed By <span>Electro BD</span></p>
      </div>
      <div class="logo">
        <span>
          <img src="@/assets/icons/business.png" alt="icon business" />
        </span>
        <span>
          <img src="@/assets/icons/trust-wave.png" alt="icon trust-wave" />
        </span>

        <span>
          <img src="@/assets/icons/norton.png" alt="icon norton" />
        </span>

        <span>
          <img src="@/assets/icons/truste.png" alt="icon truste" />
        </span>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .footer-end {
    display: flex;
    flex-direction: column;
    align-items: stretch;
    justify-content: center;

    .nav-footer {
      display: flex;
      justify-content: space-between;

      padding: 8.6rem 20rem;
      background-color: $color-bg-primary;
      border-bottom: 0.4px inset $color-primary-light-3;

      .col {
        display: flex;
        flex-direction: column;

        gap: 2rem;

        .heading {
          font-size: 1.4rem;
          font-weight: 700;
          color: $color-primary-dark;

          position: relative;

          &::after {
            content: '';
            display: block;
            width: 50%;
            height: 1px;
            background-color: $color-accent-4;

            position: absolute;
            bottom: -1rem;
            left: 0;
          }
        }

        ul {
          display: flex;
          flex-direction: column;
          align-items: start;
          justify-content: center;
          gap: 1rem;

          li > a {
            font-size: 1.3rem;
            font-weight: 400;
            color: $color-primary;
          }
        }
      }
    }

    .description-footer {
      display: flex;
      align-items: center;
      justify-content: space-between;

      padding: 1rem 20rem;

      .person-design {
        p {
          font-size: 1.3rem;
          font-weight: 500;

          span {
            font-weight: 700;
            color: $color-accent-2;
          }
        }
      }

      .logo {
        display: flex;
        align-items: stretch;
        justify-content: center;
        gap: 2rem;

        & > * {
          display: flex;
          align-items: stretch;
          justify-content: center;
        }

        span > img {
          width: 8rem;
          height: auto;
        }
      }
    }
  }
</style>
