<template>
  <div class="casePane">
    <el-row>
      <el-col :span="4" v-for="(o, index) in 10" :key="index" :offset="2">
        <el-card :body-style="{ padding: '0px' }">
          <img
            src="../assets/images/case1.jpg"
            class="image"
          />
          <div style="padding: 14px;text-align:center;">
            <span>行业案例</span>
            <div class="bottom clearfix">
              <!-- <time class="time">{{ currentDate }}</time> -->
              <el-button type="text" class="button">查看详情</el-button>
            </div>
          </div>
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  data() {
    return {
      currentDate: new Date()
    };
  }
};
</script>
<style scoped>
.time {
  font-size: 13px;
  color: #999;
}

.bottom {
  margin-top: 13px;
  line-height: 12px;
  text-align: center;
  display: flex;
  justify-content: center;
}

.button {
  padding: 0;
  float: right;
}

.image {
  width: 100%;
  display: block;
}

.clearfix:before,
.clearfix:after {
  display: table;
  content: "";
}

.clearfix:after {
  clear: both;
}
</style>