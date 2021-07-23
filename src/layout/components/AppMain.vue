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
  .app-main
    min-height: calc(100vh - 1.2rem)
    width: 100%
    position: relative
    overflow: hidden
</style>
