<template>
  <div class="nav-footer">
    <div class="container">
      <div class="option">
        <img src="../assets/buy-comics-digital-comics.png" alt="" />
        <div class="text">DIGITAL COMICS</div>
      </div>
      <div class="option">
        <img src="../assets/buy-comics-merchandise.png" alt="" />
        <div class="text">DC MERCHANDISE</div>
      </div>
      <div class="option">
        <img src="../assets/buy-comics-subscriptions.png" alt="" />
        <div class="text">SUBSCRIPTION</div>
      </div>
      <div class="option">
        <img src="../assets/buy-comics-shop-locator.png" alt="" />
        <div class="text">COMIC SHOP LOCATOR</div>
      </div>
      <div class="option">
        <img src="../assets/buy-dc-power-visa.svg" alt="" />
        <div class="text">DC POWER VISA</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../style/color.scss";
.nav-footer {
  background-color: $main-blu;
  .container {
    display: flex;
    justify-content: space-between;

    .option {
      display: flex;
      align-items: center;
      height: 80px;
      padding: 20px 0;
      color: white;

      img {
        height: 100%;
        margin-right: 6px;
      }
    }
  }
}
</style>
