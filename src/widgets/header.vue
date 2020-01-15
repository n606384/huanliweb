<template>
  <div class="header">
    <a href="/home">
      <img :src="logoimg" alt />

      <span>北京环理天下咨询有限公司</span>
    </a>
  </div>
</template>

<script>
export default {
  data() {
    return {
      logoimg: require("@/assets/images/logo.png")
    };
  }
};
</script>
<style scoped>
</style>