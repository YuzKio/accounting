<template>
  <div>
    <app-main class="app-main"/>
    <navbar />
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import AppMain from './components/AppMain'
export default {
  name: 'index',
  components: {AppMain, Navbar}
}
</script>

<style lang="stylus" scoped>
</style>
