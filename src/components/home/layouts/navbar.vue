<template>
  <el-menu :default-active="activeIndex" class="nav" text-color="rgba(88, 74, 74, 1)" mode="horizontal"
           @select="handleSelect">
    <li class="nav-item">
      <el-input v-model="input" class="el-input--small" placeholder="请输入内容"></el-input>
    </li>
    <el-menu-item index="1">GoLang</el-menu-item>
    <el-menu-item index="2">PHP</el-menu-item>
    <el-menu-item index="3">JavaScript</el-menu-item>
  </el-menu>

</template>

<script>
  export default {
    data() {
      return {
        activeIndex: '1',
        input: ''
      };
    },
    methods: {
      handleSelect(key, keyPath) {
        console.log(key, keyPath);
      }
    }
  }
</script>

<style >
  .header .nav {
    float: right;
    background: transparent;
    padding: 0;
    margin: 0;
  }


  .el-menu--horizontal > .el-menu-item:not(.is-disabled):focus, .el-menu--horizontal > .el-menu-item:not(.is-disabled):hover {
    background: none;
  }

  .nav-item {
    margin: 0;
    float: left;
    list-style: none;
    position: relative;
    cursor: pointer;
    right: 20px;
    top: 17px;
  }

  .el-menu.el-menu--horizontal{
    border-bottom:none;
  }

  .el-input--small input {
    height: 32px;
    background-color: rgba(255, 255, 255, 0.2);
  }

</style>
