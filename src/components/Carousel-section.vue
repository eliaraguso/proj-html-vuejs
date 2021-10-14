<template>
  <section id="carousel-section">
      <img src="../assets/img/client-logos-1.png" alt="">
      <img src="../assets/img/client-logos-2.png" alt="">
      <img src="../assets/img/client-logos-3.png" alt="">
      <img src="../assets/img/client-logos-4.png" alt="">
  </section>
</template>

<script>
export default {
    name: 'Carousel',

}
</script>

<style lang="scss" scoped>
    #carousel-section {
        height: 330px;
        background-image: url(../assets/img/rgb-gradient-bar-for-logo-carrasel.jpg);
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
        display: flex;
        justify-content: center;
        align-items: center;
    }

</style>