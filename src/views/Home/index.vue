<template>
  <div class="container">
    <home-header></home-header>
    <home-bill></home-bill>
  </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeBill from './components/Bill'
export default {
  name: 'index',
  components: {HomeBill, HomeHeader}
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .container
    background: $bgColor
</style>
