<template>
  <div>
    <div class="food-container">
      <div class="images">
        <img src="@/assets/icons/BodyIcons/unsplash1.svg" alt="" />
        <div>
          <img src="@/assets/icons/BodyIcons/unsplash.svg" alt="" />
          <img src="@/assets/icons/BodyIcons/unsplash2.svg" alt="" />
        </div>
      </div>
      <div class="text">
        <h4>About Us</h4>
        <h1>
          Food is an important <br />
          part Of a balanced Diet
        </h1>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque diam <br />
          pellentesque bibendum non dui volutpat fringilla bibendum. Urna, elit <br />
          augue urna, vitae feugiat pretium donec id elementum. Ultrices mattis <br />
          vitae mus risus. Lacus nisi, et ac dapibus sit eu velit in consequat.
        </p>
        <div class="buttons">
          <button id="show-more">Show More</button>
          <button id="play">
            <img src="@/assets/icons/BodyIcons/Play.svg" alt="" />
          </button>
          <h3>Watch Video</h3>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.food-container {
  display: flex;
  justify-content: flex-start;
  gap: 60px;
  padding: 131px var(--global-padding) 0px 131px;
  .text {
    h4 {
      font-family: Miniver;
      font-size: 18px;
      color: var(--primary-color);
    }
    h1 {
      font-weight: 700;
      font-size: 48px;
      line-height: 56px;
      color: var(--gray1);
    }
    p {
      padding-top: 32px;
    }
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
    .buttons {
      margin-top: 32px;
      display: flex;
      align-items: center;
      gap: 16px;
      #play {
        width: 60px;
        height: 60px;
        border-radius: 50%;
        border: none;
        background-color: var(--primary-color);
        cursor: pointer;
      }
      h3 {
        font-size: 16px;
        font-weight: 700;
      }
    }
  }

  .images {
    display: flex;
    gap: 30px;
  }
}
</style>
