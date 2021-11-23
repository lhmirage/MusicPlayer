<template>
  <div class="headerBar">
    <div class="left">
    </div>
    <div class="center">
      <div class="buttons">
      </div>
      <div class="search">
        <el-popover
          placement="bottom"
          width="300"
        >
         <el-input
            placeholder="请输入内容"
          >
          </el-input>
        </el-popover>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderBar'

}
</script>

<style>

</style>