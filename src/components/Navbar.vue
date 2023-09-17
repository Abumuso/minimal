<template>
  <div class="navbar-head">
    <div class="nav">
      <div class="logo">
        <img :src="img" alt="" />
        <p>minimal</p>
      </div>
      <ul>
        <li>process</li>
        <li>project</li>
        <li>team</li>
        <li>contact</li>
      </ul>
    </div>
  </div>
  <div class="navbar-body">
    <div class="bodytext">
      <p>Making brands stand out</p>
      <p>is our obsession</p>
      <p class="line"></p>
      <p>Let us help your brand stand out.</p>
    </div>
  </div>
  <div class="navbar-foot">
    <div class="foottext">
      <p>
        Minimalist is a full-service digital creative agency located in Ontorio
        Canada. We focus on design, consulting, technology, and photography.
        We’ve been building unique digital products, platforms, and experiences
        for the past 6 years. Let us help your company grow.
      </p>
      <p>Get in Touch</p>
    </div>
  </div>
</template>

<script setup>
import img from "../assets/navlogo.jpg";
</script>

<style lang="scss" scoped>
.navbar-head {
  width: 1440px;
  height: 106px;
  display: flex;
  justify-content: center;
}
.nav {
  margin: 18px auto;
  width: 940px;
  height: 70px;
  display: flex;
  justify-content: space-between;
}
.logo {
  width: 155px;
  height: 70px;
  display: flex;
  gap: 18px;
}
.logo p {
  margin: 13px 0 19px 0;
  width: 72px;
  color: #333;
  font-size: 22px;
  font-style: normal;
  font-weight: 400;
  line-height: 38px;
  text-transform: uppercase;
}
ul {
  display: flex;
  height: 45px;
  padding: 23px 0px 0px 34px;
  justify-content: flex-end;
  align-items: flex-start;
  gap: 34px;
}

.navbar-body {
  display: flex;
  width: 1440px;
  height: 391px;
  background-image: url("../assets/navimg2.jpg");
}
.bodytext {
  margin: 98px auto;
  width: 940px;
  height: 195px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.bodytext p:nth-child(1) {
  margin-top: 7px;
  color: #fff;
  text-align: center;
  font-size: 44px;
  font-style: normal;
  font-weight: 400;
  line-height: 55px;
  text-transform: uppercase;
}
.bodytext p:nth-child(2) {
  color: #fff;
  text-align: center;
  font-size: 43px;
  font-style: normal;
  font-weight: 400;
  line-height: 55px;
  text-transform: uppercase;
}
.bodytext p:nth-child(3) {
  width: 80px;
  height: 2px;
  background: #fff;
  margin-top: 28px;
}
.bodytext p:nth-child(4) {
  margin-top: 25px;
  color: rgba(255, 255, 255, 0.81);
  text-align: center;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
}

.navbar-foot {
  width: 1440px;
  height: 289px;
  display: flex;
  background: #fefec9;
}
.foottext {
  margin: 60px 250px 61px 250px;
  width: 940px;
  height: 168px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
}
.foottext p:nth-child(1) {
  color: #47474f;
  text-align: center;
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: 25px;
}
.foottext p:nth-child(2) {
    padding: 13px 34px 20px 34px;
    color: #47474f;
    text-align: center;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px;
    border: 1px solid;
}
</style>
