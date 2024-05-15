<template>
    <div class="main-content">
      <OverFlow />
      <div class="content">
        <h1 class="head">The world’s destination <span>for design</span></h1>
      </div>
      <div class="para">
        <h3 class="parac">Get inspired by the work of millions of top-rated designers & agencies around the world.
        </h3>
      </div>
      <div class="SignGet">
        <a href="#">Get Started</a>
      </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.main-content {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  margin-top: 78px;
}
.content {
  display: flex;
  align-items: center;
}
.head>span {
  display: flex;
  align-items: center;
  justify-content: center;
}
.head {
  display: flex;
  font-family: "Source Serif 4", Georgia, serif;
  margin: 40px auto 24px;
  font-weight: 200;
  font-size: 72px;
  letter-spacing: -0.5px;
  flex-direction: column;
}
.parac {
  font-size: 23px;
  display: flex;
  justify-content: center;
  font-weight: 350;
  align-items: center;
}

.SignGet {
  background-color: black;
  height: 50px;
  color: #ffff;
  /* width: 100px; */
  border-radius: 29px;
  /* color: #ffff; */
  margin-top: 36px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0 24px;
  align-content: center;
}

.SignGet>a {
  color: #ffff;
  font-size: 14px;
}
@media only screen and (min-width: 601px) and (max-width: 900px) {
  .parac {
    font-size: 20px !important;
  }}
@media only screen and (max-width: 600px) {
  .head {
    font-size: 38px !important;
    width: 100% !important;
    font-weight: 400;
    letter-spacing: -0.5px;
    line-height: 56px;
    margin: 40px auto 24px;
  }
  .para {
    width: 80%;
  }

  .parac {
    font-size: 16px !important;
    line-height: 24px;
  }}
</style>