<template>
  <div id="app">
    <div class="header-top">
      <div class="container">
        <div class="header-top_flex">
          <div class="header-top_left">
            <p>
              Call for Free Estimate! Everyday from 09:00 AM:
              <span>800-987-8830</span>
            </p>
          </div>
          <div class="header-top_right">
            <a href="#"><i class="fab fa-facebook-square"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-youtube"></i></a>
            <a href="#"><i class="fab fa-whatsapp"></i></a>
          </div>
        </div>
      </div>
    </div>
    <header class="header">
      <div class="container">
        <div class="header-nav">
          <div class="header-nav_left">
            <img src="img/header/logo.png" alt="" />
          </div>
          <div class="header-nav_center">
            <ul>
              <li><a href="#" class="active">Home</a></li>
              <li><a href="#">About</a></li>
              <li><a href="#">Services</a></li>
              <li><a href="#">Offers</a></li>
              <li><a href="#">Pricing</a></li>
              <li><a href="#">Reviews</a></li>
              <li><a href="#">Contact</a></li>
            </ul>
          </div>
          <div class="header-burger">
            <i class="fas fa-bars"></i>
          </div>
          <div class="general-yellow-btn">Request an Estimate</div>
        </div>
        <div class="header-body">
          <h2>SAVE TIME FOR YOUR FAMILY.</h2>
          <h1>WE CLEAN FOR YOU!</h1>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua ut enim
            ad minim veniam.
          </p>
          <div class="general-yellow-btn">SEE OUR OFFER</div>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
import Header from "./Header.vue";

export default {
  name: "app",
  components: {
    Header,
  },
};
</script>

<style scoped>
.header-top {
  width: 100%;
  margin: 0;
  padding: 10px 0;

  background-color: #ecf6fe;
}

.header-top_flex {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.header-top_left p {
  margin: 0;
  color: #008aff;
  font: 300 15px var(--josefin);
}

.header-top_left p span {
  font-weight: 600;
}

.header-top_right a {
  display: inline-block;
  margin-left: 10px;

  font-size: 15px;
  text-decoration: none;
}

.header {
  padding: 64px 0 216px 0;

  background: url("../img/header/person.png") top right no-repeat,
    url("../img/header/background.png") center/cover no-repeat;
}

.header .header-burger {
  display: none;
}

.header-nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.header-nav_center ul {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0;

  list-style-type: none;
}

.header-nav_center ul li {
  margin-right: 5px;
}

.header-nav_center ul li:last-child {
  margin: 0;
}

.header-nav_center ul li a {
  width: 107px;
  height: 43px;
  display: inline-block;
  border-radius: 22px;
  display: flex;
  justify-content: center;
  align-items: center;

  font: 400 16px var(--josefin);
  color: #008aff;
  text-decoration: none;

  transition: all 0.5s ease 0s;
}

.header-nav_center ul li a:hover {
  background-color: #0068c4;
  color: #fff;
}

.header-nav_center ul li a:active {
  color: #fff;
  background-color: #005096;
}

.header-nav_center ul li a.active {
  width: 107px;
  height: 43px;
  display: flex;
  justify-content: center;
  align-items: center;

  font: 400 16px var(--josefin);
  color: #fff;
  text-decoration: none;

  outline: none;
  border-radius: 22px;
  background-color: #008aff;
  transition: all 0.5s ease 0s;
}

.header-nav_center ul li a.active:hover {
  background-color: #0071d4;
}

.header-nav_center ul li a.active:active {
  background-color: #0062b8;
}

.header-body h2 {
  margin-top: 200px;

  font: 300 33px var(--josefin);
  color: #008aff;
}

.header-body h1 {
  margin-top: 38px;

  font: 400 68px var(--josefin);
  color: #13287e;
}

.header-body p {
  max-width: 700px;
  margin-top: 60px;

  font: 300 20px var(--josefin);
  line-height: 35px;
  color: #474747;
}

.header-body .general-yellow-btn {
  margin-top: 49px;
  width: 219px;
  height: 68px;
  border-radius: 33px;
}
</style>