<template>
  <div class="footer">
    <div class="link">
      <div class="container">
        <div class="list">
          <div class="in-block">
            <ul class="in-block">
              <li>DC COMICS</li>
              <li><a href="">Characters</a></li>
              <li><a href="">Comics</a></li>
              <li><a href="">Movies</a></li>
              <li><a href="">Tv</a></li>
              <li><a href="">Games</a></li>
              <li><a href="">Videos</a></li>
              <li><a href="">News</a></li>
            </ul>
            <ul>
              <li>SHOP</li>
              <li><a href="">Shop DC</a></li>
              <li><a href="">Shop DC Collectibles</a></li>
            </ul>
          </div>
          <ul class="in-block">
            <li>DC</li>
            <li><a href="">Terms Of Use</a></li>
            <li><a href="">Privacy policy (New)</a></li>
            <li><a href="">Ad Choices</a></li>
            <li><a href="">Advertising</a></li>
            <li><a href="">Jobs</a></li>
            <li><a href="">Subscriptions</a></li>
            <li><a href="">Talent Workshops</a></li>
            <li><a href="">CPSC Certificates</a></li>
            <li><a href="">Ratings</a></li>
            <li><a href="">Shop Help</a></li>
            <li><a href="">Contacts Us</a></li>
          </ul>
          <ul class="in-block">
            <li>DC COMICS</li>
            <li><a href="">Characters</a></li>
            <li><a href="">Comics</a></li>
            <li><a href="">Movies</a></li>
            <li><a href="">Tv</a></li>
            <li><a href="">Games</a></li>
            <li><a href="">Videos</a></li>
            <li><a href="">News</a></li>
          </ul>
        </div>
        <div class="img">
          <img src="../assets/dc-logo-bg.png" alt="" />
        </div>
      </div>
    </div>
    <div class="social">
      <div class="container">
        <div class="button">SING-UP NOW!</div>
        <div class="link-social">
          <span>FOLLOW US</span>
          <img src="../assets/footer-facebook.png" alt="" />
          <img src="../assets/footer-twitter.png" alt="" />
          <img src="../assets/footer-youtube.png" alt="" />
          <img src="../assets/footer-pinterest.png" alt="" />
          <img src="../assets/footer-periscope.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../style/color.scss";
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  .list {
    width: 50%;
  }
  .img {
    width: 50%;
    position: relative;

    img {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
    }
  }
}
.in-block {
  display: inline-block;
  width: calc(100% / 3);
  vertical-align: top;
}
.link {
  background-image: url(../assets/footer-bg.jpg);
  overflow: hidden;
  padding: 24px 0;
  ul {
    list-style: none;
    li {
      padding: 3px 0;
      a {
        text-decoration: none;
        color: #aaa;
        font-size: 10px;
      }

      &:first-child {
        padding: 6px 0;
        font-weight: bold;
        color: white;
      }
    }
  }
  img {
    width: 100%;
  }
}

.social {
  background-color: #303030;
  padding: 12px 0;
  .button {
    border: 2px solid $main-blu;
    color: white;
    padding: 6px;
  }

  .link-social {
    display: flex;
    align-items: center;
    span {
      color: $main-blu;
      margin-right: 6px;
    }
    img {
      height: 20px;
      margin-right: 6px;
    }
  }
}
</style>
