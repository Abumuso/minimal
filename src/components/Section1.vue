<template>
    <div class="section1">
      <div class="container">
        <div class="bigbox">
          <p>How we make brands thrive</p>
          <p class="line"></p>
            <div class="box">
              <div class="card">
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
              <div class="card">
                <div class="pic">
                  <img src="../assets/box2-removebg-preview.jpg" alt="" />
                </div>
                <p>design a solution</p>
                <p>
                  Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut
                  commodo diam libero vitae erat.
                </p>
              </div>
              <div class="card">
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
      </div>
    </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.section1 {
  width: 100%;
  display: flex;
  justify-content: center;
}
.bigbox{
  margin:69px auto;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;


}
.bigbox p {
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
  width: 100%;
  margin-top: 43px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}
.card {
  width: 300px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.pic {
  width: 100%;
  background: #f5f5f5;
}
.pic img {
  margin: 50px auto;
}
.card p:nth-child(2) {
  margin-top: 38px;
  color: #333;
  text-align: center;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  text-transform: uppercase;
}
.card p:nth-child(3) {
  margin-top: 20px;
  padding-bottom: 5px;
  color: #333;
  text-align: center;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: 22px;
  text-transform: none;
}

.conteiner {
  .bigbox {
    width: 100%;
  }
  .box {
    width: 100%;
  }
}
</style>
