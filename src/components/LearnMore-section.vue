<template>
  <section id="learnMore-section">
    <div class="learn-box" id="first-box">
      <h3>Emergency Care</h3>
      <img src="../assets/img/wave-divider.png" alt="">
      <p>
        Sed ut perspiciatis unde omnis iste natus error sit voluptatem
        accusantium doloremque laudantium, totam rem aperiam, eaque
      </p>
      <a href="#">LEARN MORE</a>
    </div>
     <div class="learn-box" id="second-box">
      <h3>Expert Diagnostics</h3>
      <img src="../assets/img/wave-divider.png" alt="">
      <p>
        Sed ut perspiciatis unde omnis iste natus error sit voluptatem
        accusantium doloremque laudantium, totam rem aperiam, eaque
      </p>
      <a href="#">LEARN MORE</a>
    </div>
     <div class="learn-box" id="third-box">
      <h3>Superb Rehabilitation</h3>
      <img src="../assets/img/wave-divider.png" alt="">
      <p>
        Sed ut perspiciatis unde omnis iste natus error sit voluptatem
        accusantium doloremque laudantium, totam rem aperiam, eaque
      </p>
      <a href="#">LEARN MORE</a>
    </div>
  </section>
</template>

<script>
export default {
  name: "Learn",
};
</script>

<style lang="scss" scoped>
    #learnMore-section {
        color: white;
        display: flex;
        .learn-box {
            text-align: center;
            width: calc(100% / 3);
            padding: 40px 30px 50px 30px;
            line-height: 48px;
            h3 {
                font-weight: 300;
                letter-spacing: 1px;
                font-size: 22px;
            }
            p {
                margin-bottom: 15px;
                font-weight: 300;
            }
            a {
                color: white;
                text-decoration: none;
                border: 2px solid white;
                padding: 13px 29px;
                font-weight: 400;
                
            }
        }
        #first-box,
        #second-box,
        #third-box {
          a {
          transition: .2s ease-in-out;

          }
        }
        #first-box {
            background-color: #3bafbf;
            a:hover {
                background-color: white;
                color: #3bafbf;
            }
        }
        #second-box {
            background-color: #3697c3;
             a:hover {
                background-color: white;
                color: #3697c3;
            }
        }
        #third-box {
            background-color: #327ec7;
             a:hover {
                background-color: white;
                color: #327ec7;
            }
        }
    }
</style>