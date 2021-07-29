<template>
  <div>
    <summary-header></summary-header>
    <summary-card></summary-card>
  </div>
</template>

<script>
import SummaryHeader from './components/Header'
import SummaryCard from './components/Card'
export default {
  name: 'Summary',
  components: {SummaryHeader, SummaryCard}
}
</script>
