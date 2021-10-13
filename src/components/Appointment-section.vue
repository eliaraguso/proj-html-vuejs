<template>
  <section id="appointment-section">
    <div class="container">
      <h2>Make An Appointment</h2>
      <div class="separator"></div>
      <h3>
        Sed ut perspiciatis unde omnis iste natus error sit voluptatem
        accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab
        illo inventore veritatis et quasi architecto beatae
      </h3>
      <form action="#">
        <input type="text" name="" id="name" placeholder="Name*" />
        <input type="email" name="" id="email" placeholder="Email*" />
        <input type="tel" name="" id="tel" placeholder="Phone number*" />
        <input type="date" name="" id="date" />
        <textarea
          name=""
          id="textarea"
          cols="40"
          rows="5"
          placeholder="How can we help?*"
        ></textarea>
        <button type="submit" id="submit">MAKE AN APPOINTMENT</button>
      </form>
    </div>
  </section>
</template>

<script>
export default {
  name: "Appointment",
};
</script>

<style lang="scss" scoped>
// Appointment section
#appointment-section {
  background-image: url(../assets/img/make-an-appointment.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  padding: 150px 0;
  .container {
    width: 33%;
    margin: auto;
    color: white;
    text-align: center;
    .separator {
      border-bottom: 2px solid;
      width: 300px;
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
      letter-spacing: 1px;
      margin-bottom: 50px;
    }
  }

  //   Form
  form {
    // border: 5px solid green;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    #name,
    #email,
    #tel,
    #date {
      width: calc(50% - 10px);
      background: transparent;
      border: 1px solid rgba(183, 203, 206, 0.77);
      margin-bottom: 30px;
      color: rgb(170, 169, 169);
      padding: 0 10px;
      height: 50px;
    }
    #textarea,
    #submit {
      width: 100%;
    }
    #name {
    }
    #email {
    }
    #tel {
    }
    #date {
    }
    #textarea {
      background: transparent;
      border: 1px solid rgba(183, 203, 206, 0.77);
      color: rgb(170, 169, 169);
      padding: 10px 10px;
      margin-bottom: 30px;
    }
    #submit {
        font-size: 18px;
        color: white;
        padding: 17px 0;
        background-color: #3bafbf;
        letter-spacing: 2px;
        border: transparent;
        border-radius: 2px;
        cursor: pointer;
        &:hover {
            background-color: #00a8bf;
        }
    }
  }
}
</style>