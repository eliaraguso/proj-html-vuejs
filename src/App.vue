<template>
  <div id="app">
    <Header :headerMenu="headerMenu" />
    <Main />
    <Footer :footerMenu="footerMenu"/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
  data() {
    return {
      headerMenu: [
        {
          text: "HOME",
          color: "home",
          hover: " home",
        },
        {
          text: "ABOUT",
          color: "white",
          hover: " home",
          active: "active",
        },
        {
          text: "DEPARTMENTS",
          color: "white",
          active: "active",
        },
        {
          text: "ARTICLES",
          color: "white",
          active: "active",
        },
        {
          text: "MAKE APPOINTMENT",
          color: "white",
          background: "appointment",
        },
      ],
      footerMenu: [
        
      ]
    };
  },
};
</script>

<style lang="scss">
@import "./assets/style/common.scss";
@import url("https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap");
#app {
  font-family: "Lato", sans-serif;
}
</style>
