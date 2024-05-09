<template>
<div class="orange">
      <div class="mean">

        <div class="orange_con">
          <div class="orange_head">
            <h1>
              Find your next designer today
            </h1>
          </div>
          <div class="orange_para">
            <span>The world’s leading brands use Dribbble to hire creative talent. </span>
            <span>Browse millions of top-rated portfolios to find your perfect </span>
            <span>creative match.</span>
          </div>
        </div>
        <div class="started">
          <div class="browsee">
            <a href="#">Get Started now</a>
          </div>
          <div class="browsee_light">
            <a href="#">Learn about hiring</a>
          </div>

        </div>
        <div class="links">
          <span> Are you a designer? <a href="#" class="under">Join Dribble</a></span>
        </div>
      </div>

    </div>
</template>

<style scoped>
@media only screen and (max-width: 600px) {

    .orange_head>h1{
  font-size: 40px !important;

}
.orange_head{
  text-align:center;
}
.orange_para{
  font-size: 14px !important;
        line-height: inherit;

}
}
.orange_con {
  display: flex;
  flex-direction: column;
  justify-content: center;
  font-family: "Source Serif 4", Georgia, serif;
  align-items: center;
  height: 352px;
  width: 680px;
}
.mean {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: inherit;
  width: inherit;
}
.orange_head>h1 {
  max-width: 350px;
  font-size: 54px;
}

.orange_para {
  max-width: 600px;
  margin: 0 auto;
  font-size: 20px;
  line-height: 36px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  font-family: "Mona Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
}

.orange {
  background-color: #ffda79;
  height: 600px;
  width: inherit;
  margin-top: 120px;
}
.started {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 26px;
}
.browsee_light>a {
  border: 1px solid #0d0c22;
  background: white;
  height: 60px;
  font-weight: 600;
  font-size: 14px;
  color: black;
  padding: 17px;
  border-radius: 30px;
}

.browsee>a {
  border: 1px solid #0d0c22;
  background: black;
  height: 60px;
  font-weight: 600;
  font-size: 14px;
  color: white;
  padding: 17px;
  border-radius: 30px;
}
.links {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 35px;
}

.links>span {
  font-size: 20px;
  font-family: "Mona Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
}
</style>