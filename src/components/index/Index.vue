<template>
  <el-container>
    <el-header>
      <ems-header></ems-header>
    </el-header>
    <el-main>
      <h1>主体</h1>
    </el-main>
    <el-footer>
      <h1>底部</h1>
    </el-footer>
  </el-container>

</template>

<script>

  export default {
    name: "Index",
    data() {
      return {
        name: this.$route.params.name
      }
    }
  }
</script>

<style scoped>
  .el-header {
    margin-top: -3%;
  }
</style>
