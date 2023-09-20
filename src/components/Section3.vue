<template>
  <div class="section">
    <div class="container">
      <div class="bigbox3">
        <p>our team</p>
        <p class="line"></p>
        <div class="box">
          <div class="card1">
            <img src="../assets/pic1.jpg" alt="" />
            <p class="name">Ron Swanson</p>
            <p class="prof">Founder</p>
            <div class="icons">
              <span><img src="../assets/twit.svg" alt="" /></span>
              <span><img src="../assets/in.svg" alt="" /></span>
              <span><img src="../assets/email.svg" alt="" /></span>
            </div>
          </div>
          <div class="card1">
            <img src="../assets/pic2.jpg" alt="" />
            <p class="name">Ron Swanson</p>
            <p class="prof">Founder</p>
            <div class="icons">
              <span><img src="../assets/twit.svg" alt="" /></span>
              <span><img src="../assets/in.svg" alt="" /></span>
              <span><img src="../assets/email.svg" alt="" /></span>
            </div>
          </div>
          <div class="card1">
            <img src="../assets/pic3.jpg" alt="" />
            <p class="name">Ron Swanson</p>
            <p class="prof">Founder</p>
            <div class="icons">
              <span><img src="../assets/inst.svg" alt="" /></span>
              <span><img src="../assets/twit.svg" alt="" /></span>
              <span><img src="../assets/be.svg" alt="" /></span>
              <span><img src="../assets/earth.svg" alt="" /></span>
              <span><img src="../assets/email.svg" alt="" /></span>
            </div>
          </div>
          <div class="card1">
            <img src="../assets/pic4.jpg" alt="" />
            <p class="name">Ron Swanson</p>
            <p class="prof">Founder</p>
            <div class="icons">
              <span><img src="../assets/face.svg" alt="" /></span>
              <span><img src="../assets/twit.svg" alt="" /></span>
              <span><img src="../assets/email.svg" alt="" /></span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.section {
  display: flex;
  justify-content: center;
}
.bigbox3 {
  width: 100%;
  // margin-top: 68.95px;
  padding: 69px 0;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.bigbox3 p {
  color: #333;
  text-align: center;
  font-size: 23px;
  font-style: normal;
  font-weight: 400;
  line-height: 36px;
  text-transform: uppercase;
}
.line {
  margin-top: 28px;
  width: 80px;
  height: 2px;
  background: rgba(0, 0, 0, 0.09);
}
.box {
  margin-top: 42.95px;
  display: flex;
  width: 100%;
  justify-content: center;
  align-items: flex-start;
  flex-wrap: wrap;
}
.card1 {
  margin-top: 0px;
  margin-bottom: 20px;
  width: 230px;
  height: 339px;
  // display: flex;
  // flex-direction: column;
  // align-items: center;
}
.card1 img {
  width: 220px;
  height: 220px;
}
.card1 .name {
  margin-top: 20px;
  color: #333;
  text-align: center;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  text-transform: uppercase;
}
.card1 .prof {
  margin-top: 6px;
  color: #333;
  text-align: center;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 0px;
}
.icons {
  display: flex;
  width: 220px;
  height: 35px;
  // padding: 11.047px 60px 9.953px 61px;
  justify-content: center;
  align-items: flex-start;
  gap: 14px;
}
.icons span img {
  width: 14px;
  height: 14px;
}
// .conteiner {
//   .bigbox3 {
//     width: 100%;
//   }
//   .box {
//     width: 100%;
//   }
// }
</style>
