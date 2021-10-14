<template>
  <div id="facilities-section">
    <div class="container">
      <img src="../assets/img/icon-7.png" alt=""/>
        <h2>TOUR OUR FACILITIES</h2>
        <div class="separator"></div>
        <h3>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
          cupiditate neque libero, quod magnam nesciunt necessitatibus
          accusantium, sed fugit adipisci quos alias dolorem? Necessitatibus
          eveniet modi placeat hic architecto sunt!
        </h3>
        <a href="#"><img src="../assets/img/play-icon.png" alt=""></a>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Facilities'
}
</script>

<style lang="scss" scoped>
  #facilities-section {
    height: 793px;
    background-image: url(../assets/img/paralax-bg-tour-facilities.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    .container {
      // border: 5px solid white;
      width: 33%;
      text-align: center;
      .separator {
        border-bottom: 1px solid;
        width: 300px;
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
        padding-bottom: 40px;
      }
    }
  }
</style>