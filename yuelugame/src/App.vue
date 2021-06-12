<template>
  <div id="app">
    <el-container>
      <el-header>{{ title }}</el-header>
      <el-main><router-view /></el-main>
    </el-container>
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      title: '岳麓游戏'
    }
  }
}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.el-header{
  background-color: #B3C0D1;
  text-align: center;
  line-height: 60px;
  font-family: "微软雅黑";
}
</style>
