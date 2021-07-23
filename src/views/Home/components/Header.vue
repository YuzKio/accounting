<template>
 <div class="header-wrapper">
   <div class="header-left">日常</div>
   <div class="header-right">卡包</div>
 </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
  .header-wrapper
    overflow: hidden
    height: 1.2rem
    line-height: 1.2rem
    padding: 0 .14rem
    .header-left
      float: left
      font-size: .58rem
    .header-right
      float: right
      font-size: .44rem
</style>
