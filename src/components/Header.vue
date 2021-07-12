<template>
  <div class="header container">
    <div>
      <img src="../assets/dc-logo.png" alt="" />
    </div>
    <ul>
      <li>CHARACTERS</li>
      <li>COMICS</li>
      <li>MOVIES</li>
      <li>TV</li>
      <li>GAMES</li>
      <li>COLLECTIBLES</li>
      <li>VIDEOS</li>
      <li>FANS</li>
      <li>NEWS</li>
      <li>SHOP</li>
    </ul>
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
.header {
  display: flex;
  height: 80px;
  padding: 20px;
  justify-content: space-between;
  font-size: 14px;
  font-weight: 400;
  img {
    height: 100%;
  }
}

ul {
  display: flex;
  list-style: none;
  text-align: center;
  height: 100%;
  li {
    padding: 0 12px;
    height: 100%;
    line-height: 40px;

    &:hover {
      border-bottom: 2px solid $main-blu;
    }
  }
}
</style>
