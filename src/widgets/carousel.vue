<template>
  <div class="sliderPane">
    <el-carousel indicator-position="inside">
    <el-carousel-item v-for="item in 4" :key="item">
        <img src="../assets/images/sliderimg1.jpg" alt="">
      <h3>{{ item }}</h3>
    </el-carousel-item>
  </el-carousel>
  </div>
</template>

<script>
export default {};
</script>
<style scoped>
.el-carousel__item img{
    width: 100%;
}
.el-carousel__item h3 {
  color: #475669;
  font-size: 16px;
  opacity: 0.75;
  line-height: 200px;
  margin: 0;
}

.el-carousel__item:nth-child(2n) {
  background-color: #99a9bf;
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: #d3dce6;
}
</style>