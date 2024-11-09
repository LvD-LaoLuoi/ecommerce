<script setup></script>

<template>
  <div class="news-letter">
    <div class="sign-up">
      <span>
        <img src="@/assets/icons/newletters.png" alt="icon newsletter" />
        <p>Sign Up For Our Newsletter</p>
      </span>

      <form action="#" class="subscribe-email">
        <input type="text" placeholder="Enter your email address" />

        <button type="submit">
          <p>SUBSCRIBE NOW</p>
        </button>
      </form>
    </div>
    <div class="socials">
      <span class="link-social facebook">
        <img src="@/assets/icons/facebook.png" alt="icon facebook" />
        <p>FACEBOOK</p>
      </span>

      <span class="link-social twitter">
        <img src="@/assets/icons/twitter.png" alt="icon twitter" />
        <p>TWITTER</p>
      </span>

      <span class="link-social youtube">
        <img src="@/assets/icons/youtube.png" alt="icon youtube" />
        <p>YOUTUBE</p>
      </span>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .news-letter {
    display: flex;
    justify-content: space-between;
    align-items: center;

    padding: 3.2rem 1.2rem;
    background-color: $color-bg-primary;

    .sign-up {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex: 1 1 auto;
      gap: 2rem;
      border: none;

      span {
        display: flex;
        align-items: center;
        gap: 1rem;
        border: none;

        & > * {
          border: none;
        }

        img {
          width: 4rem;
        }

        p {
          font-size: 1.8rem;
          font-weight: 700;
          color: $color-primary-dark;
        }
      }

      .subscribe-email {
        display: flex;
        flex: 1 1 0;
        align-items: center;
        border: none;
        border-radius: 2px;

        & > * {
          align-self: stretch;
          padding: 1.2rem 1.8rem;
          border: none;
        }

        input {
          flex: 1 1 0;
          background-color: $color-bg-secondary;
        }

        button {
          display: flex;
          align-items: center;
          flex-shrink: 0;
          gap: 0.6rem;

          color: $color-secondary;
          background-color: $color-accent-2;

          cursor: pointer;
          border-top-right-radius: 2px;
          border-bottom-right-radius: 2px;

          p {
            font-size: 1.2rem;
            font-weight: 600;
          }
        }
      }
    }

    .socials {
      display: flex;
      justify-content: end;
      align-items: center;
      gap: 1rem;
      flex: 1 1 auto;
      border: none;

      .link-social {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 0.6rem;

        cursor: pointer;
        border-radius: 2px;
        padding: 1.2rem 1.8rem;
        color: $color-secondary;

        & > * {
          border: none;
        }

        img {
          width: 1.4rem;
        }

        p {
          font-size: 1.2rem;
          font-weight: 600;
        }
      }

      .facebook {
        background-color: $color-accent-6;
      }

      .twitter {
        background-color: $color-accent-5;
      }

      .youtube {
        background-color: $color-accent-4;
      }
    }
  }
</style>
