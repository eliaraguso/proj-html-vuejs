<template>
  <header>
    <!-- Header Top section -->
    <section id="header-top">
      <img src="../assets/img/medical_logo_1x_light.png" alt="" />
      <nav>
        <ul>
          <li
            :class="item.background"
            v-for="(item, index) in headerMenu"
            :key="index"
          >
            <a :class="[item.color, item.active]" href="#">{{ item.text }}</a>
          </li>
        </ul>
      </nav>
    </section>

    <!-- Header Top section -->
    <section id="header-bottom">
      <div class="container">
        <div class="header-info">
          <h1>Caring <span>For Life</span></h1>
          <p class="info-text">
            Kind words can be short and easy to speak, but their echoes are
            truly endless. Avada Health focuses on you as if it was our own
            family.
          </p>
          <a href="#">LEARN MORE</a>
        </div>
      </div>
    </section>
  </header>
</template>


<script>
export default {
  name: "Header",
  props: {
    headerMenu: Array,
  },
};
</script>



<style lang="scss" scoped>
// --------------Header----------------------
header {
  background-image: url("../assets/img/header-image-homepage.jpg");
  height: 1000px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  border: 6px solid orangered;
}

// --------------Header Top----------------------
#header-top {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border: 5px solid peru;
  padding: 0 30px;
  height: 116px;
  img {
    height: 45px;
  }
  ul {
    list-style: none;
    li {
      display: inline-block;
      margin: 0 20px;
      a {
        text-decoration: none;
      }
    }
  }
}

// --------------Header Bottom----------------------
#header-bottom {
  border: 5px solid green;
  height: calc(100% - 116px);
  .container {
    border: 5px solid black;
    width: 70%;
    margin: auto;
    height: 100%;
    display: flex;
    align-items: center;
    .header-info {
      border: 5px solid yellow;
      width: 50%;
      color: white;
      h1 {
        font-size: 80px;
        font-weight: 300;
        span {
          color: #39afbb;
        }
      }
      .info-text {
        font-size: 26px;
        font-weight: 300;
        margin: 50px 0;
      }
      a {
        color: white;
        background-color: #39afbb;
        padding: 17px 40px;
        font-size: 18px;
        text-decoration: none;
        letter-spacing: 2px;
      }
    }
  }
}

// -------------Common Scss---------
.appointment {
  background-color: #39afbb;
  border-radius: 5px;
  padding: 10px 30px;
}

.white {
  color: white;
}

.home {
  color: #39afbb;
}

.active:hover {
  color: #39afbb;
}
</style>