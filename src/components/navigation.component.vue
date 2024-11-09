<script setup></script>

<template>
  <header class="header-section">
    <h1 class="header-section__logo">Electro<span class="header-section__logo--bd">.BD</span></h1>
    <form action="#" class="header-section__search">
      <select name="category">
        <option value="all">All Category</option>
      </select>
      <input type="text" placeholder="What are you looking for..." />

      <button type="submit">
        <p>SEARCH NOW</p>
        <img src="@/assets/icons/search.png" alt="search icon" />
      </button>
    </form>

    <div class="header-section__user-nav">
      <span>
        <img src="@/assets/icons/sign-in.png" alt="sign in" />
        <p>Sign In</p>
      </span>
      <span>
        <img src="@/assets/icons/messages.png" alt="messages" />
        <p>Messages</p>
      </span>
      <span>
        <img src="@/assets/icons/orders.png" alt="orders" />
        <p>Orders</p>
      </span>
      <span>
        <img src="@/assets/icons/shop-cart.png" alt="shop cart" />
        <p>Shop Cart</p>
      </span>
    </div>
  </header>
</template>

<style lang="scss" scoped>
  .header-section {
    display: flex;
    align-items: center;
    gap: 8rem;

    width: 100%;
    padding: 2rem 20rem;
    background-color: $color-bg-primary;
    border-bottom: 0.4px inset $color-primary-light-3;

    &__logo {
      display: inline-block;
      font-family: 'Poppins', sans-serif;
      font-size: 3.6rem;
      font-weight: 400;

      color: $color-accent-1;

      &--bd {
        color: $color-accent-2;
        font-weight: 600;
      }
    }

    &__search {
      display: flex;
      flex: 1 1 0;
      align-items: center;
      border-radius: 2px;

      & > * {
        align-self: stretch;
        padding: 1.7rem 2.2rem;
        border: none;
      }

      select {
        color: $color-primary;
        background-color: $color-bg-secondary;
      }

      input {
        flex: 1 1 0;
        border-top: 1px solid $color-bg-secondary;
        border-bottom: 1px solid $color-bg-secondary;
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

        img {
          width: 1.4rem;
        }

        p {
          font-size: 1.2rem;
          font-weight: 600;
        }
      }
    }

    &__user-nav {
      display: flex;
      justify-content: end;
      align-items: center;
      gap: 1rem;

      span {
        display: flex;
        flex-direction: column;
        align-items: center;

        width: 6rem;

        img {
          width: 3.6rem;
        }

        p {
          font-size: 1.3rem;
        }
      }
    }
  }
</style>
