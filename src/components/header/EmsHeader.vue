<template>
      <el-row >
        <el-col :span="4" class="ems_header_title">测试企业·综合能源管理系统</el-col>
        <el-col :span="4" class="ems_header_title"></el-col>
      </el-row>
</template>

<script>

    export default {
        name: "emsHeader"
    }
</script>

<style scoped>
  .el-row {
    height: 100%;
    background: url("./static/imgs/top-bj-12.png") no-repeat center;
  }

  .ems_header_title {
    font-size: 25px;
    color: #ffffff;
    margin-top: 0.6%;
  }

</style>
