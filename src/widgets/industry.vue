<template>
  <div class="industryPane">
    <el-tabs class="industry" type="border-card">
      <el-tab-pane>
        <span slot="label">
          <i class="el-icon-date"></i> 工业
        </span>
        <div class="block">
          <el-timeline>
            <el-timeline-item timestamp="" placement="top">
              <el-card>
                <h4>工业品市场</h4>
                <p></p>
              </el-card>
            </el-timeline-item>
            <el-timeline-item timestamp="" placement="top">
              <el-card>
                <h4>发电厂</h4>
                <p>王小虎 提交于 2018/4/3 20:46</p>
              </el-card>
            </el-timeline-item>
            <el-timeline-item timestamp="" placement="top">
              <el-card>
                <h4>LNG</h4>
                <p>王小虎 提交于 2018/4/2 20:46</p>
              </el-card>
            </el-timeline-item>
          </el-timeline>
        </div>
      </el-tab-pane>
      <el-tab-pane label="环保">环保</el-tab-pane>
      <el-tab-pane label="建筑">建筑</el-tab-pane>
      <el-tab-pane label="地产">地产</el-tab-pane>
      <el-tab-pane label="旅游">旅游</el-tab-pane>
      <el-tab-pane label="智能家居">智能家居</el-tab-pane>
      <el-tab-pane label="医疗教育">医疗教育</el-tab-pane>
    </el-tabs>
  </div>
</template>

<script>
export default {};
</script>
<style scoped>
.industry {
  /* width: 100%; */
  /* display: flex;
  
  height: 700px; */
  justify-content: center;
}
</style>