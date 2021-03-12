<template>
  <div id="app">
    <Homepage />
    <Information />
    <Review />
    <Insight />
    <Corporate />
    <Foot />
  </div>
</template>

<script>
import Homepage from './components/Homepage.vue'
import Information from './components/Information.vue'
import Review from './components/Review.vue'
import Insight from './components/Insight.vue'
import Corporate from './components/Corporate.vue'
import Foot from './components/Foot.vue'


export default {
  name: 'App',
  components: {
    Homepage,
    Information,
    Review,
    Insight,
    Corporate,
    Foot
  }
}
</script>

<style>

</style>
