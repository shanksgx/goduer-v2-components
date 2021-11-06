<template>
  <div>
    <el-button type="primary">主要按钮</el-button>
    <el-button type="success" plain>主要按钮</el-button>
    <el-button type="danger" round>主要按钮</el-button>
  </div>
</template>
<script>
import { Button as elButton } from 'element-ui'
import 'element-ui/lib/theme-chalk/index.css'
export default {
  components:{
    elButton
  }
}
</script>

<style>
</style>
