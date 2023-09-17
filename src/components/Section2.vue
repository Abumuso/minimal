<template>
  <div class="section">
    <div class="bigbox">
      <p>Recent projects</p>
      <p class="line"></p>
      <div class="boxhead">
        <div class="box1">
          <img src="../assets/s2b1.jpg" alt="wood" />
          <div class="text">
            <p>woods</p>
            <p>Photography</p>
          </div>
        </div>
        <div class="box1">
          <img src="../assets/s2b2.jpg" alt="wood" />
          <div class="text">
            <p>path</p>
            <p>Website • Photography</p>
          </div>
        </div>
        <div class="box1">
          <img src="../assets/s2b3.jpg" alt="wood" />
          <div class="text">
            <p>darkness</p>
            <p>Website</p>
          </div>
        </div>
      </div>
      <div class="boxbody">
        <div class="box4">
          <img src="../assets/s2b1.jpg" alt="wood" />
          <div class="text">
            <p>woods</p>
            <p>Photography</p>
          </div>
        </div>
        <div class="box5">
          <img src="../assets/s2b2.jpg" alt="wood" />
          <div class="text">
            <p>path</p>
            <p>Website • Photography</p>
          </div>
        </div>
        <div class="box6">
          <img src="../assets/s2b3.jpg" alt="wood" />
          <div class="text">
            <p>darkness</p>
            <p>Website</p>
          </div>
        </div>
      </div>
      <div class="boxfoot">
        <div class="box1">
          <img src="../assets/s2b1.jpg" alt="wood" />
          <div class="text">
            <p>woods</p>
            <p>Photography</p>
          </div>
        </div>
        <div class="box1">
          <img src="../assets/s2b2.jpg" alt="wood" />
          <div class="text">
            <p>path</p>
            <p>Website • Photography</p>
          </div>
        </div>
        <div class="box1">
          <img src="../assets/s2b3.jpg" alt="wood" />
          <div class="text">
            <p>darkness</p>
            <p>Website</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.section {
  width: 1440px;
  height: 1469px;
  display: flex;
  flex-direction: column;
  background: #f5f5f5;
  align-items: center;
}
.section .bigbox {
  margin-top: 69px;
  width: 940px;
  height: 1330.953px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.section .bigbox p {
  margin-top: 10px;
  width: 230px;
  color: #333;
  text-align: center;
  font-size: 23px;
  font-style: normal;
  font-weight: 400;
  line-height: 36px;
  text-transform: uppercase;
}
.section .bigbox .line {
  margin-top: 28px;
  margin-bottom: 43px;
  width: 80px;
  height: 2px;
  background: rgba(0, 0, 0, 0.09);
}

.bigbox .boxhead {
  display: flex;
  width: 960px;
  padding: 0px 10.047px 20px 10px;
  justify-content: center;
  align-items: flex-start;
  gap: 20px;
}
.boxhead .box1 {
  width: 300px;
  height: 84px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.text {
  margin-bottom: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 300px;
  height: 84px;
  background: #fff;
}
.text p:nth-child(1) {
  margin-top: 19px;
  color: #333;
  text-align: center;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  text-transform: uppercase;
}
.text p:nth-child(2) {
  margin-top: 4px;
  margin-bottom: 21px;
  color: #333;
  font-family: "Times New Roman", Times, serif;
  text-align: center;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  text-transform: none;
}
.bigbox .boxbody {
  display: flex;
  width: 960px;
  //   padding: 50px 10.047px 20px 10px;
  justify-content: center;
  align-items: flex-start;
  gap: 20px;
}
.bigbox .boxfoot {
  display: flex;
  width: 960px;
  //   padding: 50px 10.047px 20px 10px;
  justify-content: center;
  align-items: flex-start;
  gap: 20px;
}
</style>
