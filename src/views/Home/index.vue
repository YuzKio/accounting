<template>
  <div>
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
