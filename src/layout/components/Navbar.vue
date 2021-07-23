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
      <div class="navbar-item-content">
        <svg class="icon" aria-hidden="true">
          <use xlink:href="#icon-chaxun"></use>
        </svg>
      </div>
      <div class="navbar-item-desc">统计</div>
    </div>
    <div class="navbar-item">
      <div class="navbar-item-content">
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
    z-index: 1000
    display: flex
    position: fixed
    width: 100%
    height: 1.2rem
    left: 0
    bottom: 0
    box-shadow: 0 0 5px #b6b4b4
    background: #fff
    .navbar-item
      flex: 1
      box-sizing: border-box
      padding: .1rem
      text-align: center
      .navbar-item-content
        font-size: .6rem
      .navbar-item-desc
        color: #5f5f5f
</style>
