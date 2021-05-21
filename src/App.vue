<template>
  <div id="app">
    <h1>悦音湾内容发布系统</h1>
    <!-- 路由出口 -->
    <router-view/>
    <el-button>默认按钮</el-button>
    <el-button type="danger">默认按钮</el-button>
  </div>
</template>

<script>
export default{
  name: 'App',
  data () {
    return {}
  },
  methods: {},
  created () {}
}
</script>

<style lang="less"></style>
