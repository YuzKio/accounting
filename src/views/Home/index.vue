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
  name: 'Home',
  components: {HomeBill, HomeHeader}
}
</script>

<style lang="stylus" scoped>
@import '~styles/varibles.styl'
.container
  position: absolute
  width: 100%
  height: 100%
  background: $bgColor
</style>
