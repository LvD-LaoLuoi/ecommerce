<script setup></script>

<template>
  <div class="sub-navigation">
    <div class="sub-navigation__department">
      <img src="@/assets/icons/menu.png" alt="all department" />
      <p>All Department</p>
    </div>

    <div class="sub-navigation__nav-units">
      <div class="sub-navigation__nav">
        <span>
          <p>HOME</p>
          <img src="@/assets/icons/arrow-down.svg" alt="icon home" />
        </span>

        <span>
          <p>SHOP</p>
          <img src="@/assets/icons/arrow-down.svg" alt="icon home" />
        </span>

        <span>
          <p>PROMOTION</p>
          <img src="@/assets/icons/arrow-down.svg" alt="icon home" />
        </span>

        <span>
          <p>BLOG</p>
          <img src="@/assets/icons/arrow-down.svg" alt="icon home" />
        </span>

        <span>
          <p>SPECIAL</p>
          <img src="@/assets/icons/arrow-down.svg" alt="icon home" />
        </span>

        <span>
          <p>PAGES</p>
          <img src="@/assets/icons/arrow-down.svg" alt="icon home" />
        </span>

        <span>
          <p>VENDOR</p>
          <img src="@/assets/icons/arrow-down.svg" alt="icon home" />
        </span>
      </div>

      <div class="sub-navigation__units">
        <span> Get The App </span>
        <select name="money-units">
          <option value="usd">English-USD</option>
        </select>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .sub-navigation {
    display: flex;
    align-items: center;
    gap: 4rem;

    width: 100%;
    padding: 1rem 20rem 0 20rem;
    background-color: $color-bg-primary;

    & > * {
      display: flex;
      align-items: center;
      align-self: stretch;
      border: none;
    }

    &__department {
      justify-content: start;
      gap: 0.5rem;
      flex: 1 1 18%;
      padding: 1.8rem 0;
      color: $color-secondary;
      background-color: $color-accent-2;

      img {
        margin-left: 1rem;
        width: 1.8rem;
        height: 1.8rem;
      }

      p {
        width: 100%;
        font-size: 1.4rem;
        font-weight: 600;
        letter-spacing: 0.8px;
      }
    }

    &__nav-units {
      justify-content: space-between;
      flex-basis: calc(82% - 4rem);
      width: 100%;

      & > * {
        display: flex;
        align-items: center;
        align-self: stretch;
      }
    }

    &__nav {
      gap: 1.2rem;
      transition: all 0.3s;

      span {
        display: flex;
        padding: 1rem 1.2rem;
        gap: 0.2rem;
        cursor: pointer;
      }

      p {
        color: $color-primary-dark;
        font-size: 1.4rem;
        font-weight: 700;
      }

      img {
        visibility: hidden;
        width: 1.6rem;
      }

      span:hover {
        border-radius: 2px;
        background-color: $color-bg-secondary;
      }

      span:hover img {
        visibility: visible;
      }
    }

    &__units {
      gap: 1rem;

      span,
      select {
        font-size: 1.3rem;
        color: $color-primary;
      }

      select {
        padding: 0 2rem;
      }

      span {
        cursor: pointer;
      }
    }
  }
</style>
