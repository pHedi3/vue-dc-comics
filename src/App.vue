<template>
  <div id="app">
    <Header />
    <Main />
    <NavFooter />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import NavFooter from "./components/NavFooter.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    NavFooter,
    Footer,
  },
};
</script>

<style lang="scss">
@import "./style/app.scss";
</style>
