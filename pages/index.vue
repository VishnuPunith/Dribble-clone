<template>
  <div class="container">
    <!-- navbar :: start -->

    <NavBar />

    <!-- navabar :: end -->

    <!-- mainContent :: start (Text is there eg First ) -->

      <HeadPara />

    <!-- mainContent :: end -->

    <!-- slidercard :: start -->

    <SliderCard />

    <!-- slidercard :: end -->

    <!-- cardSlide :: start (4 grid images there inside this like Aqua)-->

    <CardsSlide />

    <!-- cardSlide :: end -->
    
    <!-- CardMiddle :: start (Middle orange card contains contents) -->

    <CardMiddle />

    <!-- CardMiddle :: end -->
 
    <!-- pausePlay :: start (In last slider small slider marquee from left to right once we hover it will stop)-->

    <PausePlay />

    <!-- pausePlay :: start -->

    <!-- Footer :: Start -->

    <div class="foot_text">
      <DibbleLogo />
      <FooterContent />
      <SocialMedia />
    </div>

    <!-- Footer :: end -->

  </div>

</template>




<style scoped>


@media only screen and (max-width: 600px) {

  .foot_text {
    height: 200px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

 
}

#__layout {
  overflow-x: hidden;
}

body {
  margin: 0;
  padding: 0;
  font-family: "Mona Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;

}


.container {
  height: 100vh;
  max-width: 100vw;
  background-color: #f8f7f4;
  padding: 0;
  margin: 0;
}

::selection {
  background: rgba(255, 218, 121, 0.5);
  color: #0d0c22;
}


a {
  color: #47607b;
  -webkit-text-decoration: none;
  text-decoration: none;
  background-color: transparent;
}

</style>