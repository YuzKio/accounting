<template>
  <div class="summary-container">
    <div class="summary-header">
      <ul class="summary-nav">
        <li class="summary-nav-item">周总结</li>
        <li class="summary-nav-item">月总结</li>
        <li class="summary-nav-item">年总结</li>
      </ul>
    </div>
    <div class="summary-date">
      <div class="summary-date-left">《</div>
      <div class="summary-date-middle">
        <p class="summary-date-detail">2021年7月</p>
        <p class="summary-date-span">07/01-07/30</p>
      </div>
      <div class="summary-date-right">》</div>
    </div>
    <div class="summary-card-wrapper">
      <div class="summary-card active">
        支出
      </div>
      <div class="summary-card">
        收入
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SummaryHeader'
}
</script>

<style lang="stylus" scoped>
  .summary-container
    position: relative
    width: 100%
    .summary-header
      overflow: hidden
      box-sizing: border-box
      padding: .1rem .8rem
      .summary-nav
        display: flex
        .summary-nav-item
          flex: 1
          float: left
          text-align: center
          height: .8rem
          line-height: .8rem
    .summary-date
      overflow: hidden
      display: flex
      padding: 0 .8rem
      align-items: center
      .summary-date-left
        float: left
      .summary-date-middle
        flex: 1
        text-align: center
        padding: .1rem 0
        .summary-date-detail
          font: bold .3rem/.4rem arial,sans-serif
        .summary-date-span
          font-size: .2rem
      .summary-date-right
        float: right
    .summary-card-wrapper
      display: flex
      overflow: hidden
      box-sizing: border-box
      margin: .3rem .3rem 0 .3rem
      height: 1rem
      background: #fff
      .summary-card
        flex: 1
        float: left
        text-align: center
        height: .8rem
        font:.3rem/.8rem arial,sans-serif
        background: #f7f7f7
      .active
        top: -1rem
        background: #fff
</style>
