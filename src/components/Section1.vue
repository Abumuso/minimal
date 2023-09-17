<template>
  <div class="section1">
    <p>How we make brands thrive</p>
    <p class="line"></p>
    <div class="box">
      <div class="box1">
        <div class="pic">
          <img
            src="../assets/box1-removebg-preview.jpg
"
            alt="boxphoto" />
        </div>
        <p>SET a target</p>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse
          varius enim in eros elementum tristique.
        </p>
      </div>
      <div class="box2">
        <div class="pic">
          <img src="../assets/box2-removebg-preview.jpg" alt="" />
        </div>
        <p>design a solution</p>
        <p>
          Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut
          commodo diam libero vitae erat.
        </p>
      </div>
      <div class="box3">
        <div class="pic">
          <img src="../assets/box3-removebg-preview.jpg" alt="" />
        </div>
        <p>track the progress</p>
        <p>
          Aenean faucibus nibh et justo cursus id rutrum lorem imperdiet. Nunc
          ut sem vitae risus tristique posuere.
        </p>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.section1 {
  margin: 69px auto;
  width: 940px;
  height: 487px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.section1 p {
  margin-top: 10px;
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
  margin-top: 43px;
  display: flex;
  justify-content: center;
  gap: 20px;
}
.pic {
  width: 300px;
  height: 219px;
  background: #f5f5f5;
}
.pic img {
  margin: 50px auto;
}
.box1 {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 319.984px;
  height: 368px;
}
.box1 p:nth-child(2) {
  margin-top: 38px;
  color: #333;
  text-align: center;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  text-transform: uppercase;
}
.box1 p:nth-child(3) {
  margin-top: 20px;
  padding-bottom: 5px;
  font-family: 'Times New Roman', Times, serif;
  color: #333;
  text-align: center;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: 22px;
  text-transform: none;
}
.box2 {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 319.984px;
  height: 368px;
}
.box2 p:nth-child(2) {
  margin-top: 38px;
  color: #333;
  text-align: center;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  text-transform: uppercase;
}
.box2 p:nth-child(3) {
  margin-top: 20px;
  padding-bottom: 5px;
  font-family: 'Times New Roman', Times, serif;
  color: #333;
  text-align: center;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: 22px;
  text-transform: none;
}
.box3 {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 319.984px;
  height: 368px;
}
.box3 p:nth-child(2) {
  margin-top: 38px;
  color: #333;
  text-align: center;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  text-transform: uppercase;
}
.box3 p:nth-child(3) {
  margin-top: 20px;
  padding-bottom: 5px;
  font-family: 'Times New Roman', Times, serif;
  color: #333;
  text-align: center;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: 22px;
  text-transform: none;
}
</style>
