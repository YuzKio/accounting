<template>
  <div class="bill-container"  ref="wrapper">
    <div class="bill-wrapper">
      <div class="bill-block">
        <div class="bill-title">
          <div class="bill-title-date">2021/7/23</div>
          <div class="bill-title-sum">支出：101000</div>
        </div>
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
        <div class="bill-title">
          <div class="bill-title-date">2021/7/23</div>
          <div class="bill-title-sum">支出：101000</div>
        </div>
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
        <div class="bill-title">
          <div class="bill-title-date">2021/7/23</div>
          <div class="bill-title-sum">支出：101000</div>
        </div>
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
        <div class="bill-title">
          <div class="bill-title-date">2021/7/23</div>
          <div class="bill-title-sum">支出：101000</div>
        </div>
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
        <div class="bill-title">
          <div class="bill-title-date">2021/7/23</div>
          <div class="bill-title-sum">支出：101000</div>
        </div>
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
    <div class="bill-addButton" :style="bottomPosition">
      <div class="bill-addButton-cross"></div>
    </div>
  </div>
</template>

<script>
import Bscroll from 'better-scroll'
export default {
  name: 'HomeBill',
  data () {
    return {
      bottomPosition: {
        bottom: '0.5rem'
      }
    }
  },
  mounted () {
    this.scroll = new Bscroll(this.$refs.wrapper, {
      probeType: 3
    })
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
        .bill-title
          overflow: hidden
          .bill-title-date
            float: left
            padding-left: .3rem
            font: normal bold 0.3rem/0.5rem arial
          .bill-title-sum
            float: right
            padding-right: .3rem
            line-height: .5rem
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
    .bill-addButton
      display: flex
      justify-content: center
      align-items: center
      position: absolute
      right: 0.3rem
      width: 1.3rem
      height: 1.3rem
      border-radius: 50%
      box-shadow: 3px 5px 5px #e8d39a
      background: #FFD64E
      .bill-addButton-cross
        width: 10%
        height: 50%
        border-radius: .1rem
        background: #fff
        &:after
          position: absolute
          content: ""
          top: 50%
          width: 50%
          height: 10%
          transform: translate(-40%, -50%)
          border-radius: .1rem
          background: #fff
</style>
