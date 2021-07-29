<template>
  <section class="app-main">
    <router-view :key="key" />
  </section>
</template>

<script>
export default {
  name: 'AppMain',
  computed: {
    key () {
      return this.$route.path
    }
  }
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .app-main
    z-index: 1
    position: relative
    overflow: hidden
    min-height: calc(100vh - 1.2rem)
    width: 100%
    background: $bgColor
</style>
