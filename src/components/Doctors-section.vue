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
    <div id="doctors-bottom">
      <div class="doctor-box">
        <img src="../assets/img/doctor-1.jpg" alt="doctor photo" />
        <div class="doctor-box-bottom">
          <div class="doctor-name">JON SNOW</div>
          <div class="doctor-title">Anesthesiologist</div>
          <div class="doctor-info">
            At vero eos et accusamus et iusto odio dignissimos ducimus qui
            blanditiis praesentium voluptatum deleniti atque
          </div>
          <div class="doctor-social"></div>
          <a href="#"
            ><img src="../assets/img/facebook_icon.png" alt="facebook logo"
          /></a>
          <a href="#"
            ><img src="../assets/img/instagram_icon.png" alt="facebook logo"
          /></a>
          <a href="#"
            ><img src="../assets/img/twitter_icon.png" alt="facebook logo"
          /></a>
        </div>
      </div>
      <div class="doctor-box">
        <img src="../assets/img/doctor-2.jpg" alt="doctor photo" />
        <div class="doctor-box-bottom">
          <div class="doctor-name">TONY STARK</div>
          <div class="doctor-title">Cardiologist</div>
          <div class="doctor-info">
            At vero eos et accusamus et iusto odio dignissimos ducimus qui
            blanditiis praesentium voluptatum deleniti atque
          </div>
          <div class="doctor-social"></div>
          <a href="#"
            ><img src="../assets/img/facebook_icon.png" alt="facebook logo"
          /></a>
          <a href="#"
            ><img src="../assets/img/instagram_icon.png" alt="facebook logo"
          /></a>
          <a href="#"
            ><img src="../assets/img/twitter_icon.png" alt="facebook logo"
          /></a>
        </div>
      </div>
      <div class="doctor-box">
        <img src="../assets/img/doctor-3.jpg" alt="doctor photo" />
        <div class="doctor-box-bottom">
          <div class="doctor-name">ANNA SMITH</div>
          <div class="doctor-title">Nurse Practitioner</div>
          <div class="doctor-info">
            At vero eos et accusamus et iusto odio dignissimos ducimus qui
            blanditiis praesentium voluptatum deleniti atque
          </div>
          <div class="doctor-social"></div>
          <a href="#"
            ><img src="../assets/img/facebook_icon.png" alt="facebook logo"
          /></a>
          <a href="#"
            ><img src="../assets/img/instagram_icon.png" alt="facebook logo"
          /></a>
          <a href="#"
            ><img src="../assets/img/twitter_icon.png" alt="facebook logo"
          /></a>
        </div>
      </div>
    </div>
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
  padding-top: 130px;
  padding-bottom: 100px;
}

// Doctors top section
#doctors-top {
  // border: 5px solid brown;
  width: 33%;
  margin: auto;
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
  }
}

// Doctors bottom section
#doctors-bottom {
  width: 70%;
  margin: 80px auto;
  display: flex;
  justify-content: space-evenly;
  // border: 5px solid red;
  .doctor-box:hover {
    transform: scale(1.2);
  }
  .doctor-box {
    // border: 5px solid green;
    width: 369px;
    font-size: 18px;
    font-weight: 300;
    .doctor-box-bottom {
      padding: 35px;
      line-height: 38px;
      color: #333c4e;
      background-color: white;
      .doctor-info {
        margin: 30px 0;
        color: #7e8890;
      }
      img {
        width: 35px;
        margin-right: 15px;
      }
     
    }
  }
}
</style>