<template>
  <div class="card-container">
    <div class="card-chart">
      暂无数据
    </div>
  </div>
</template>

<script>
export default {
  name: 'SummaryCard'
}
</script>

<style lang="stylus" scoped>
  .card-container
    position: relative
    width: auto
    height: 8.5rem
    box-sizing: border-box
    margin: 0 .3rem .3rem .3rem
    border-radius: 0 0 .1rem .1rem
    background: #fff
    .card-chart
      position: absolute
      top: 50%
      left: 50%
      transform: translate(-50%, -50%)
</style>
