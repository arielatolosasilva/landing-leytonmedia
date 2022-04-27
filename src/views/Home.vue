<template>
  <div class="home">
    <div class="row">
      <div class="col-sm-12 col-01">
        <Header></Header>
      </div>
    </div>
      <div class="row center-md">
      <div class="col-sm-12  col-md-7 col-lg-8 col-02">
        <Buttons></Buttons>
      </div>
    </div>
    <div class="row center-sm">
      <div class="col-sm-8 col-md-6 ">
        <InfoIcons></InfoIcons>
      </div>
        <div class="col-sm-8 col-md-6 ">
        <ImgHome></ImgHome>
      </div>
    </div>
    <div class="row center-sm">
<div class="col-sm-10">
<Footer></Footer>
</div>
    </div>
  </div>
</template>

<script>
import Header from "../components/Home/Header";
import Buttons from "../components/Home/Buttons"
import InfoIcons from "../components/Home/InfoIcons"
import ImgHome from "../components/Home/Img"
import Footer from "../components/Home/Footer"
export default {
  name: "Home",
  components: {
    Header,
    Buttons,
    InfoIcons,
    ImgHome,
    Footer
  },
};
</script>
<style scoped>
.col-01{
  margin-top: 1rem
}
</style>
