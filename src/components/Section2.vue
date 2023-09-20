<template>
  <div class="section">
    <div class="conteiner">
      <div class="bigbox">
        <p>Recent projects</p>
        <p class="line"></p>
        <div class="boxhead">
          <div class="box">
            <img src="../assets/s2b1.jpg" alt="wood" />
            <div class="text">
              <p>woods</p>
              <p>Photography</p>
            </div>
          </div>
          <div class="box">
            <img src="../assets/s2b2.jpg" alt="wood" />
            <div class="text">
              <p>path</p>
              <p>Website • Photography</p>
            </div>
          </div>
          <div class="box">
            <img src="../assets/s2b3.jpg" alt="wood" />
            <div class="text">
              <p>darkness</p>
              <p>Website</p>
            </div>
          </div>
          <div class="box">
            <img src="../assets/s2b4.jpg" alt="wood" />
            <div class="text">
              <p>waves</p>
              <p>Photography</p>
            </div>
          </div>
          <div class="box">
            <img src="../assets/s2b5.jpg" alt="wood" />
            <div class="text">
              <p>drops</p>
              <p>Website • Photography</p>
            </div>
          </div>
          <div class="box">
            <img src="../assets/s2b6.jpg" alt="wood" />
            <div class="text">
              <p>ocean</p>
              <p>Website</p>
            </div>
          </div>
          <div class="box">
            <img src="../assets/s2b7.jpg" alt="wood" />
            <div class="text">
              <p>town</p>
              <p>Photography</p>
            </div>
          </div>
          <div class="box">
            <img src="../assets/s2b8.jpg" alt="wood" />
            <div class="text">
              <p>mountain</p>
              <p>Website • Photography</p>
            </div>
          </div>
          <div class="box">
            <img src="../assets/s2b9.jpg" alt="wood" />
            <div class="text">
              <p>camera</p>
              <p>Website</p>
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
  width: 100%;
  display: flex;
  justify-content: center;
  background: #f5f5f5;
}
.bigbox {
  margin-top: 69px;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.bigbox p {
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
.bigbox .line {
  margin-top: 28px;
  margin-bottom: 43px;
  width: 80px;
  height: 2px;
  background: rgba(0, 0, 0, 0.09);
}

.boxhead {
  display: flex;
  width: 100%;
  padding: 0px 10.047px 20px 10px;
  justify-content: center;
  flex-wrap: wrap;
  align-items: flex-start;
  gap: 20px;
}
.box {
  width: 290px;
  height: 384px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
img {
  width: 100%;
}
.text {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
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
  text-align: center;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  text-transform: none;
}

.conteiner {
  .bigbox1 {
    width: 100%;
  }
  .boxhead {
    width: 100%;
  }
}
</style>
