<template>
  <section id="welcome-section">
    <div class="container">
      <div id="welcome-top">
        <h2>Welcome to Avada Health</h2>
        <h3>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora optio
          nam odio consequuntur. Sequi fugit eaque cupiditate recusandae
          suscipit maiores ipsum!
        </h3>
      </div>

      <div id="welcome-bottom">
        <div class="feature-box">
          <a href="#">
            <img src="../assets/img/icon-1.png" alt="" />
            <h2>SAME DAY APPOINTMENTS</h2>
            <div class="info-box">
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            </div>
          </a>
        </div>
        <div class="feature-box">
          <a href="#">
            <img src="../assets/img/icon-2.png" alt="" />
            <h2>SAME DAY APPOINTMENTS</h2>
            <div class="info-box">
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            </div>
          </a>
        </div>
        <div class="feature-box">
          <a href="#">
            <img src="../assets/img/icon-3.png" alt="" />
            <h2>SAME DAY APPOINTMENTS</h2>
            <div class="info-box">
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            </div>
          </a>
        </div>
        <div class="feature-box">
          <a href="#">
            <img src="../assets/img/icon-4.png" alt="" />
            <h2>SAME DAY APPOINTMENTS</h2>
            <div class="info-box">
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            </div>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Welcome",
};
</script>

<style lang="scss" scoped>
// Welcome section
#welcome-section {
//   border: 5px solid black;
  height: 679px;
  font-weight: 300;

  h2,
  h3 {
    font-weight: 300;
  }

  //   Container
  .container {
    // border: 5px solid green;
    width: 70%;
    margin: auto;
    text-align: center;
    height: 100%;
    display: flex;
    flex-wrap: wrap;
    padding: 100px 0;

    // Welcome Top section
    #welcome-top {
    //   border: 5px solid salmon;
      width: 60%;
      margin: auto;
      color: rgb(51, 60, 78);
      h2 {
        font-size: 46px;
      }
      h3 {
        font-size: 22px;
        line-height: 48px;
      }
    }

    // Welcome Bottom section
    #welcome-bottom {
    //   border: 5px solid brown;
      display: flex;
      margin: auto;
      justify-content: space-between;
      .feature-box {
        // border: 5px solid greenyellow;
        width: calc(100% / 4.5);
        color: #747474;
        a {
          text-decoration: none;
          color: #333c4e;
        }
        a:hover {
            h2 {
          color: #39afbb;

            }
        }

        h2 {
          font-size: 22px;
          padding: 30px 0;
        }
        .info-box {
          line-height: 38px;
        }
      }
    }
  }
}
</style>