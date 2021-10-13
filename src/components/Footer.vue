<template>
  <footer>
    <div id="footer-top">
      <div id="footer-top-left">
        <img
          src="../assets/img/medical_logo_1x_dark.png"
          alt="Avada Health logo image"
        />
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Numquam,
          natus, accusantium porro ipsa assumenda incidunt sequi est soluta
          quasi quod nihil facere velit minus quae fugit exercitationem dicta
          quo doloremque.
        </p>
        <h3>LEARN MORE ABOUT US</h3>
        <div class="socials">
          <a href="#"><img src="../assets/img/facebook_icon.png" alt="" /></a>
          <a href="#"><img src="../assets/img/twitter_icon.png" alt="" /></a>
          <a href="#"><img src="../assets/img/instagram_icon.png" alt="" /></a>
          <a href="#"><img src="../assets/img/youtube_icon.png" alt="" /></a>
        </div>
      </div>
      <div id="footer-top-center">
        <h3>CONTACT INFORMATION</h3>
        <div class="separator"></div>
        <p>121 King Street, London United Kingdom</p>
        <p>1.800.458.556</p>
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2484.130918603307!2d-0.23237278423056662!3d51.4924649796327!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48760e48221944e1%3A0xee0d9e6eec2d2523!2s121%20King%20St%2C%20London%20W6%209JG%2C%20Regno%20Unito!5e0!3m2!1sit!2sit!4v1634136524672!5m2!1sit!2sit"
          width="100%"
          height="220px"
          style="border: 0"
          allowfullscreen=""
          loading="lazy"
        ></iframe>
      </div>
      <div id="footer-top-right">
        <h3>MEDICAL DEPARTMENTS</h3>
        <div class="separator"></div>
        <ul>
          <li>a</li>
          <li>a</li>
          <li>a</li>
          <li>a</li>
          <li>a</li>
          <li>a</li>
        </ul>
        <div class="button">
            <a href="#">VIEW OUR DEPARTMENTS</a>
        </div>
      </div>
    </div>
    <div id="footer-bottom">
      <p>
        © Copyright 2012 - 2021 | Avada Theme by <a href="#">ThemeFusion</a> |
        All Rights Reserved | Powered by <a href="#">WordPress</a>
      </p>
    </div>
  </footer>
</template>


<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
// Footer
footer {
  font-weight: 300;
  color: #747474;
  line-height: 38px;
}

// Footer top
#footer-top {
  display: flex;
  justify-content: space-between;
  border: 5px solid salmon;
  padding: 80px;
  h3 {
    font-weight: 300;
    font-size: 18px;
    letter-spacing: 1px;
  }
  .separator {
    border: 1px solid rgb(59, 175, 191);
    width: 40px;
    margin: 17px 0;
  }
  //    Footer top left
  #footer-top-left {
    border: 5px solid greenyellow;
    width: calc(100% / 3);
    h3 {
      margin: 30px 0;
    }
    .socials {
      width: 100%;
      img {
        width: 35px;
        margin-right: 10px;
      }
    }
  }

  //    Footer top center
  #footer-top-center {
    border: 5px solid greenyellow;
    width: calc(100% / 3);
    iframe {
      margin-top: 20px;
    }
  }

  //    Footer top right
  #footer-top-right {
    border: 5px solid greenyellow;
    width: calc(100% / 3);
    ul {
        list-style: none;
    }
    .button {
        width: 100%;
        border: 5px solid black;
    }
    a {
      font-size: 18px;
      color: white;
      padding: 17px 0;
      background-color: #3bafbf;
      letter-spacing: 2px;
      text-decoration: none;
    }
  }
}

// Footer bottom
#footer-bottom {
  font-size: 14px;
  font-weight: 300;
  line-height: 31.5px;
  padding: 24px 80px;
  background-color: #f7f7f7;
  color: #7e8890;
  a {
    color: #2b2b2b;
    text-decoration: none;
    &:hover {
      color: #3bafbf;
    }
  }
}
</style>