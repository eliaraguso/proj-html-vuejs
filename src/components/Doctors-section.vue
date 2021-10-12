<template>
  <section id="doctors-section">
    <!-- Doctors section top -->
    <div id="doctors-top">
      <img src="../assets/img/icon-5.png" alt="" />
      <h2>MEET OUR DOCTORS</h2>
      <div class="separator"></div>
      <h3>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde cupiditate
        neque libero, quod magnam nesciunt necessitatibus accusantium, sed fugit
        adipisci quos alias dolorem? Necessitatibus eveniet modi placeat hic
        architecto sunt!
      </h3>
    </div>

    <!-- Doctors section bottom -->
    <div id="doctors-bottom"></div>
  </section>
</template>

<script>
export default {
  name: "Doctors",
};
</script>

<style lang="scss" scoped>
// Doctors section
#doctors-section {
  background-color: #f7f7f7;
}
#doctors-top {
  border: 5px solid brown;
  width: 33%;
  margin: auto;
  text-align: center;
  .separator {
    border-bottom: 1px solid;
    width: 45%;
    margin: 50px auto;
    border-color: #d1d1d1;
  }
  h2 {
    font-size: 46px;
    font-weight: 300;
  }
  h3 {
    font-size: 22px;
    font-weight: 300;
    line-height: 48px;
  }
}
</style>