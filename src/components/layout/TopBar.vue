<template>
  <el-row class="top-bar">
    <el-col :span="24">
      <div class="head-wrap"><router-link to="/" class="logo"><i class="el-icon-setting"></i> 公会管理后台<!-- Vue-Admin-Base --></router-link></div>
    </el-col>
    <div class="logout">退出</div>
  </el-row>
</template>

<script>
export default {
  name: 'TopBar',
  data () {
    return {
    }
  },
  methods: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  .top-bar {
    height: 60px;
    position: relative;
    z-index: 1002;
    background: #409eff;
    color: #ffffff;
  }
  .head-wrap {
    line-height: 60px;
  }
  .logo {
    display: inline-block;
    line-height: 60px;
    padding: 0 20px;
    font-size: 16px;
    color: #ffffff;
    text-decoration: none;
  }
  .logout {
    cursor: pointer;
    position: absolute;
    right: 25px;
    top: 21px;
    font-size: 14px;

  }
</style>
