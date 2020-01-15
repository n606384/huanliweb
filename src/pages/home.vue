<template>
  <div class="homeContainer">
    <HeaderAim></HeaderAim>
    <menus></menus>
    <div class="main">
      <carousel></carousel>
      
      <industry></industry>
      <br>
      <case></case>      
      <Footer></Footer>
    </div>
    
  </div>
</template>

<script>
import HeaderAim from "@/widgets/header";
import Menus from "@/widgets/menus";
import Carousel from "@/widgets/carousel";
import Case from "@/widgets/case";
import Industry from "@/widgets/industry";
import Footer from "@/widgets/footer";

export default {
  name: "Home",
  components: {
    HeaderAim,
    Menus,
    Carousel,
    Case,
    Industry,
    Footer
  },
  data() {
    return {
      logoimg: require("@/assets/images/logo.png")
    };
  }
};
</script>
<style lang="scss" scoped>
</style>