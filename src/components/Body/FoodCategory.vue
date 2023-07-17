<template>
  <div class="food-category__container">
    <div class="text">
      <h1>Food Category</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. <br />
        Varius sed pharetra dictum neque massa congue
      </p>
    </div>
    <div class="food-category__list">
      <button><img src="@/assets/icons/BodyIcons/CaretRight.svg" alt="" /></button>
      <div class="food-container">
        <img src="@/assets/icons/BodyIcons/cake.svg" alt="" />
        <h3>Grandi Italiano</h3>
        <h5>26 Item</h5>
      </div>
      <div class="food-container">
        <img src="@/assets/icons/BodyIcons/cake.svg" alt="" />
        <h3>Grandi Italiano</h3>
        <h5>26 Item</h5>
      </div>
      <div class="food-container">
        <img src="@/assets/icons/BodyIcons/cake.svg" alt="" />
        <h3>Grandi Italiano</h3>
        <h5>26 Item</h5>
      </div>
      <div class="food-container">
        <img src="@/assets/icons/BodyIcons/cake.svg" alt="" />
        <h3>Grandi Italiano</h3>
        <h5>26 Item</h5>
      </div>
      <button><img src="@/assets/icons/BodyIcons/CaretLeft.svg" alt="" /></button>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.food-category__container {
  padding: 100px var(--global-padding);
  display: flex;
  flex-direction: column;
  gap: 56px;
  .text {
    display: flex;
    flex-direction: column;
    gap: 8px;
    justify-content: center;
    text-align: center;
    h1 {
      font-size: 48px;
      color: var(--gray1);
      font-weight: 700;
    }
    p {
      color: #828282;
    }
  }
  .food-category__list {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    gap: 24px;
    button {
      width: 45px;
      height: 45px;
      border: none;
      background-color: #195a00;
      border-radius: 4px;
      opacity: 0.5;
    }
    .food-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 10px;
      img {
        height: 364px;
        width: 312px;
      }
    }
  }
}
</style>
