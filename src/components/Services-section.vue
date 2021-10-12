<template>
  <section id="services-section">
    <div class="container">
      <div id="services-top">
        <img src="../assets/img/icon-6.png" alt="" />

        <h2>OUR HEALTH SERVICES</h2>
        <div class="separator"></div>
        <h3>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
          cupiditate neque libero, quod magnam nesciunt necessitatibus
          accusantium, sed fugit adipisci quos alias dolorem? Necessitatibus
          eveniet modi placeat hic architecto sunt!
        </h3>
      </div>
      <div id="services-bottom">
        <div class="services-box">
          <a href="#">
            <img src="../assets/img/icon-14.png" alt="" />
            <h2>REHABILITATION CENTER</h2>
            <div class="info-services">
              At vero eos et accusamus et iusto odio dignissimos ducimus qui
              blanditiis praesentium voluptatum deleniti atque corrupti quos
              dolores et quas
            </div>
          </a>
        </div>
        <div class="services-box">
          <a href="#">
            <img src="../assets/img/icon-15.png" alt="" />
            <h2>DENTAL IMPLANTS</h2>
            <div class="info-services">
              At vero eos et accusamus et iusto odio dignissimos ducimus qui
              blanditiis praesentium voluptatum deleniti atque corrupti quos
              dolores et quas
            </div>
          </a>
        </div>
        <div class="services-box">
          <a href="#">
            <img src="../assets/img/icon-16.png" alt="" />
            <h2>MEDICINE RESEARCH</h2>
            <div class="info-services">
              At vero eos et accusamus et iusto odio dignissimos ducimus qui
              blanditiis praesentium voluptatum deleniti atque corrupti quos
              dolores et quas
            </div>
          </a>
        </div>
        <div class="services-box">
          <a href="#">
            <img src="../assets/img/icon-11.png" alt="" />
            <h2>BLOOD BANK</h2>
            <div class="info-services">
              At vero eos et accusamus et iusto odio dignissimos ducimus qui
              blanditiis praesentium voluptatum deleniti atque corrupti quos
              dolores et quas
            </div>
          </a>
        </div>
        <div class="services-box">
          <a href="#">
            <img src="../assets/img/icon-12.png" alt="" />
            <h2>PHARMACEUTICAL SERVICE</h2>
            <div class="info-services">
              At vero eos et accusamus et iusto odio dignissimos ducimus qui
              blanditiis praesentium voluptatum deleniti atque corrupti quos
              dolores et quas
            </div>
          </a>
        </div>
        <div class="services-box">
          <a href="#">
            <img src="../assets/img/icon-13.png" alt="" />
            <h2>MEDICAL CONSUELING</h2>
            <div class="info-services">
              At vero eos et accusamus et iusto odio dignissimos ducimus qui
              blanditiis praesentium voluptatum deleniti atque corrupti quos
              dolores et quas
            </div>
          </a>
        </div>
        
      </div>
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
//   border: 5px solid black;
padding-top: 100px;
padding-bottom: 50px;
  .container {
    // border: 5px solid green;
    width: 70%;
    margin: auto;
    text-align: center;

    // Services top section
    #services-top {
    //   border: 5px solid yellow;
      width: 48%;
      margin: auto;
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
        color: #333c4e;
      }
    }

    // Services bottom section
    #services-bottom {
    //   border: 5px solid orangered;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      padding: 50px 0;
      a {
          text-decoration: none;
      }
      a:hover {
          h2 {
              color: #39afbb;
          }
      }
      .services-box {
        // border: 5px solid blue;
        width: calc(100% / 3.5);
        padding-left: 20px;
        padding-right: 20px;
        padding-top: 40px;
        padding-bottom: 40px;

        h2 {
          font-weight: 300;
          margin: 20px 0;
          color: black;
        }
        .info-services {
          font-weight: 300;
          line-height: 40px;
          color: #747474;
        }
      }
    }
  }
}
</style>