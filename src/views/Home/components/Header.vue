<template>
 <div class="header-wrapper">
   <div class="header-left">日常</div>
<!--   <div class="header-right">卡包</div>-->
 </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
@import '~styles/varibles.styl'
  .header-wrapper
    position:fixed
    overflow: hidden
    width: 100%
    height: 1.2rem
    line-height: 1.2rem
    padding: 0 .14rem
    .header-left
      float: left
      font-size: .58rem
</style>
