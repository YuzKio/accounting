<template>
  <div class="navbar">
    <div class="navbar-item">
      <div class="navbar-item-content">
        <svg class="icon" aria-hidden="true">
          <use xlink:href="#icon-qianbao"></use>
        </svg>
      </div>
      <div class="navbar-item-desc">首页</div>
    </div>
    <div class="navbar-item">
      <div class="iconfont navbar-item-content">
        <svg class="icon" aria-hidden="true">
          <use xlink:href="#icon-chaxun"></use>
        </svg>
      </div>
      <div class="navbar-item-desc">统计</div>
    </div>
    <div class="navbar-item">
      <div class="iconfont navbar-item-content">
        <svg class="icon" aria-hidden="true">
          <use xlink:href="#icon-wode"></use>
        </svg>
      </div>
      <div class="navbar-item-desc">我的</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style lang="stylus" scoped>
.navbar
  position: fixed
  left: 0
  bottom: 0
  width: 100%
  height: 10%
  box-shadow: 0 0 5px #b6b4b4
  .navbar-item
    overflow: hidden
    float: left
    width: 33.3%
    padding-bottom: .8rem
    .navbar-item-content
      text-align: center
      font-size: 2rem
    .navbar-item-desc
      text-align: center
      font-size: .6rem
      color: #7f7e7e
</style>
