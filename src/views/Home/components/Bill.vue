<template>
  <div class="bill-container"  ref="wrapper">
    <div class="bill-wrapper">
      <div class="bill-block">
        <div class="bill-date">2021/7/23</div>
        <div class="bill-item">
          <div class="bill-item-detail border-bottom">
            <div class="bill-item-type">美容</div>
            <span class="bill-item-amount">100</span>
          </div>
          <div class="bill-item-detail border-bottom">
            <div class="bill-item-type">美容</div>
            <span class="bill-item-amount">100</span>
          </div>
          <div class="bill-item-detail border-bottom">
            <div class="bill-item-type">美容</div>
            <span class="bill-item-amount">100</span>
          </div>
          <div class="bill-item-detail border-bottom">
            <div class="bill-item-type">美容</div>
            <span class="bill-item-amount">100</span>
          </div>
        </div>
      </div>
      <div class="bill-block">
        <div class="bill-date">2021/7/23</div>
        <div class="bill-item">
          <div class="bill-item-detail border-bottom">
            <div class="bill-item-type">美容</div>
            <span class="bill-item-amount">100</span>
          </div>
          <div class="bill-item-detail border-bottom">
            <div class="bill-item-type">美容</div>
            <span class="bill-item-amount">100</span>
          </div>
          <div class="bill-item-detail border-bottom">
            <div class="bill-item-type">美容</div>
            <span class="bill-item-amount">100</span>
          </div>
          <div class="bill-item-detail border-bottom">
            <div class="bill-item-type">美容</div>
            <span class="bill-item-amount">100</span>
          </div>
        </div>
      </div>
      <div class="bill-block">
        <div class="bill-date">2021/7/23</div>
        <div class="bill-item">
          <div class="bill-item-detail border-bottom">
            <div class="bill-item-type">美容</div>
            <span class="bill-item-amount">100</span>
          </div>
          <div class="bill-item-detail border-bottom">
            <div class="bill-item-type">美容</div>
            <span class="bill-item-amount">100</span>
          </div>
          <div class="bill-item-detail border-bottom">
            <div class="bill-item-type">美容</div>
            <span class="bill-item-amount">100</span>
          </div>
          <div class="bill-item-detail border-bottom">
            <div class="bill-item-type">美容</div>
            <span class="bill-item-amount">100</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Bscroll from 'better-scroll'
export default {
  name: 'HomeBill',
  mounted () {
    this.scroll = new Bscroll(this.$refs.wrapper)
  }
}
</script>

<style lang="stylus" scoped>
  .bill-container
    position: relative
    overflow: hidden
    top: 1.2rem
    left: 0
    right: 0
    bottom: 1.2rem
    min-height: calc(100vh - 2.4rem)
    width: 100%
    .bill-wrapper
      position: absolute
      left: 0
      right: 0
      .bill-block
        margin-bottom: .3rem
        .bill-date
          padding-left: .3rem
          font: normal bold 0.3rem/0.5rem arial
        .bill-item
          box-sizing: border-box
          margin: .1rem .2rem .2rem .2rem
          padding: .18rem
          border-radius: .1rem
          background: #fff
          .bill-item-detail
            overflow: hidden
            padding: .12rem .1rem
            .bill-item-type
              float: left
            .bill-item-amount
              float: right
</style>
