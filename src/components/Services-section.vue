<template>
  <section id="services-section">
    <div class="container">
      <div id="services-top">
        <img src="../assets/img/icon-6.png" alt="" />
      
      <h2>OUR HEALTH SERVICES</h2>
      <div class="separator"></div>
      <h3>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde cupiditate
        neque libero, quod magnam nesciunt necessitatibus accusantium, sed fugit
        adipisci quos alias dolorem? Necessitatibus eveniet modi placeat hic
        architecto sunt!
      </h3>
      </div>
      <div id="services-bottom"></div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Services",
};
</script>

<style lang="scss" scoped>
// Services section
#services-section {
    border: 5px solid;
  .container {
    border: 5px solid green;
    width: 70%;
    margin: auto;
    text-align: center;
    #services-top {
        border: 5px solid yellow;
        width: 48%;
        margin: auto;
        .separator {
    border-bottom: 1px solid;
    width: 45%;
    margin: 50px auto;
    border-color: #d1d1d1;
  }
  h2 {
    font-size: 46px;
    font-weight: 300;
    padding-top: 20px;
  }
  h3 {
    font-size: 22px;
    font-weight: 300;
    line-height: 48px;
  }
    }
  }
}
</style>