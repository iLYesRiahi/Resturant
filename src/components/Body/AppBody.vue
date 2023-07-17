<template>
  <div class="order__container">
    <h2 style="font-family: Miniver">Healthy & Testy Food</h2>
    <h1>
      Enjoy Healthy Life <br />
      & Testy Food.
      <img src="@/assets/icons/BodyIcons/stars.svg" alt="" />
    </h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. <br />
      Varius sed pharetra dictum neque massa congue
    </p>
    <div class="buttons">
      <button id="show-more">Show More</button>
      <button id="place-order">Place an Order</button>
    </div>
    <h5>ScrollDown</h5>
    <span></span>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Miniver&display=swap");
.order__container {
  margin-top: 260px;
  padding: 0px var(--global-padding) 0px var(--global-padding);
  h1 {
    font-weight: 700;
    font-size: 60px;
    color: var(--gray1);
  }
  h2 {
    color: var(--primary-color);
    font-size: 18px;
  }
  p {
    color: var(--gray);
  }
  h5 {
    text-align: center;
    margin-top: 159px;
    font-size: 14px;
    color: var(--gray2);
  }
  span {
    width: 1px;
    height: 60px;
    background-color: #828282;
  }
  .buttons {
    display: flex;
    justify-content: flex-start;
    gap: 16px;
    margin-top: 31px;
    #show-more {
      border: none;
      background-color: var(--primary-color);
      border-radius: 6px;
      width: 195px;
      height: 58px;
      color: white;
      font-weight: 600;
      font-size: 18px;
      &:hover {
        background-color: white;
        border: solid 1px var(--primary-color);
        color: var(--primary-color);
        transition: 0.5s ease-in-out;
      }
    }
    #place-order {
      border: solid 1px var(--primary-color);
      background-color: white;
      border-radius: 6px;
      height: 58px;
      width: 222px;
      color: var(--primary-color);
      font-weight: 600;
      font-size: 18px;
      &:hover {
        background-color: var(--primary-color);
        color: white;
        transition: 0.5s ease-in-out;
      }
    }
  }
}
</style>
