<template>
  <div class="summary">
    <ul class="summary-nav">
      <li class="summary-nav-item">周总结</li>
      <li class="summary-nav-item">月总结</li>
      <li class="summary-nav-item">年总结</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'SummaryHeader'
}
</script>

<style lang="stylus" scoped>
  .summary
    overflow: hidden
    position: relative
    width: 100%
    height: 1rem
    box-sizing: border-box
    padding: .1rem .8rem
    .summary-nav
      display: flex
      .summary-nav-item
        flex: 1
        float: left
        text-align: center
        line-height: .8rem
</style>
