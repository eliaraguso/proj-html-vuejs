<template>
  <header>
    <section id="header-top">
      <img src="../assets/img/medical_logo_1x_light.png" alt="">
      <nav>
        <ul>
          <li v-for="(item, index) in headerMenu" :key="index"><a href="#">{{item.text}}</a></li>
        </ul>
      </nav>
    </section>
    <section id="header-bottom"></section>
  </header>
</template>

<script>
export default {
    name: 'Header',
    props: {
      headerMenu: String,
    }
}
</script>

<style lang="scss" scoped>
  header {
    background-image: url("../assets/img/header-image-homepage.jpg");
    height: 1974px;
    background-repeat: no-repeat;
  }

  #header-top {
    display: flex;
    justify-content: space-between;
    ul {
      list-style: none;
      li {
      display: inline-block;
      margin: 0 20px;
      a {
        text-decoration: none;
        color: white;
      }
    }}
  }
</style>