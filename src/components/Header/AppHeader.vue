<template>
  <div class="app-header__container">
    <div class="nav-bar">
      <img src="@/assets/icons/AppHeaderIcons/Foodtuck.svg" alt="" />
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Menu</a></li>
        <li><a href="#">Blog</a></li>
        <li><a href="#">Pages</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Shop</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </div>
    <div class="icons">
      <img src="@/assets/icons/AppHeaderIcons/Search.svg" alt="" />
      <img src="@/assets/icons/AppHeaderIcons/User.svg" alt="" />
      <img src="@/assets/icons/AppHeaderIcons/Tote.svg" alt="" />
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.app-header__container {
  padding: 50px 610px 0px var(--global-padding);
  display: flex;
  justify-content: space-between;
  .nav-bar {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    gap: 94px;
    ul {
      list-style: none;
      display: flex;
      gap: 32px;
      a {
        text-decoration: none;
        color: var(--gray1);
        &:hover {
          font-weight: 700;
          text-decoration: underline 2px;
        }
      }
    }
  }
  .icons {
    display: flex;
    justify-content: flex-start;
    gap: 16px;
    img {
      cursor: pointer;
    }
  }
}
</style>
