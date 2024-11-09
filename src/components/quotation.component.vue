<script setup></script>

<template>
  <div class="quotation-section">
    <div class="heading">
      <img src="@/assets/icons/diamon.png" alt="quotation icon" />
      <p>Request For Quotation</p>
    </div>

    <div class="description">
      <div class="banner-quotation">
        <div class="details">
          <h3>Global Sourcing Marketplace</h3>
          <div class="digital 01">
            <span>
              <p class="number">234730+</p>
              <p class="text">RFQs</p>
            </span>
            <span>
              <p class="number">473000</p>
              <p class="text">Avg Quotation Duration</p>
            </span>
          </div>
          <div class="digital 02">
            <span>
              <p class="number">436872+</p>
              <p class="text">Active Suppliers</p>
            </span>

            <span>
              <p class="number">2364</p>
              <p class="text">Industries</p>
            </span>
          </div>
        </div>

        <button class="learn-more">LEARN MORE</button>
      </div>
      <div class="form-input">
        <div class="form-heading">
          <h3>One Request, Multiple Quotes</h3>
          <p>
            Assertively economica sound catalysts for change through diverse results.
            Phosfluorescently optimize enabled alignments
          </p>
        </div>

        <form action="#">
          <input type="text" placeholder="What are you looking for" />
          <div class="group-input">
            <input type="number" placeholder="Quantity" />
            <select name="category">
              <option value="all">Piece/pieces</option>
            </select>
          </div>

          <button>REQUEST FOR QUOTATION</button>
        </form>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .quotation-section {
    display: flex;
    flex-direction: column;
    gap: 1px;

    .heading {
      display: flex;
      align-items: center;
      justify-content: start;
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

    .description {
      display: flex;
      align-items: stretch;
      background-color: $color-bg-primary;

      .banner-quotation {
        flex: 1 1 50%;
        padding: 2.4rem 2.4rem 3.8rem;

        display: flex;
        flex-direction: column;
        align-items: start;
        gap: 3rem;

        background-image: url('@/assets/images/24.png');
        background-size: cover;
        background-repeat: no-repeat;
        background-position: right bottom -20px;

        .details {
          display: flex;
          flex-direction: column;
          align-items: stretch;
          gap: 1.8rem;

          flex: 1 1 50%;

          h3 {
            font-size: 2.4rem;
            font-weight: 700;
            color: $color-secondary;
            letter-spacing: 1.2px;
          }

          .digital {
            display: flex;
            align-items: center;
            justify-content: space-between;
            color: $color-secondary;

            span {
              flex: 1 1 50%;

              display: flex;
              flex-direction: column;
              align-items: start;
              gap: 0.6rem;

              .number {
                font-size: 1.8rem;
                font-weight: 700;
              }

              .text {
                font-size: 1.2rem;
                font-weight: 500;
              }
            }
          }
        }

        .learn-more {
          font-size: 1.2rem;
          font-weight: 600;
          padding: 1.2rem 2.8rem;
          border-radius: 2px;

          cursor: pointer;
          color: $color-accent-2;
          background-color: $color-bg-primary;
        }
      }

      .form-input {
        flex: 1 1 50%;
        padding: 2.4rem 2.4rem 3.8rem;

        display: flex;
        flex-direction: column;
        align-items: stretch;
        gap: 3rem;

        .form-heading {
          display: flex;
          flex-direction: column;
          align-items: start;
          gap: 1.2rem;

          h3 {
            font-size: 1.8rem;
            font-weight: 700;
            color: $color-primary-dark;
          }

          p {
            font-size: 1.2rem;
            font-weight: 500;
          }
        }

        form {
          display: flex;
          flex-direction: column;
          align-items: stretch;
          gap: 1.8rem;

          input,
          select {
            font-size: 1.2rem;
            font-weight: 500;
            border: 0.4px solid $color-bg-secondary;
            outline: none;

            padding: 1.2rem 2.8rem;
            color: $color-primary-light-1;
            border-radius: 2px;
          }

          input::placeholder {
            color: $color-primary-light-1;
          }

          button {
            align-self: start;
            font-size: 1.2rem;
            font-weight: 600;
            padding: 1.2rem 2.8rem;
            border-radius: 2px;

            cursor: pointer;
            color: $color-bg-primary;
            background-color: $color-accent-2;
            box-shadow: 0 4px 10px $color-accent-2;
          }

          .group-input {
            display: flex;
            align-items: center;

            gap: 1rem;

            input,
            select {
              flex: 1 1 50%;
            }
          }
        }
      }
    }
  }
</style>
