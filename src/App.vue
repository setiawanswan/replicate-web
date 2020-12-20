<template>
  <div id="app">
    <Navbar msg="Ini Navbar" />
    <Homepage />
    <Information />
    <Insight />
    <Corporate />
    <Foot />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Homepage from './components/Homepage.vue'
import Information from './components/Information.vue'
import Insight from './components/Insight.vue'
import Corporate from './components/Corporate.vue'
import Foot from './components/Foot.vue'


export default {
  name: 'App',
  components: {
    Homepage,
    Navbar,
    Information,
    Insight,
    Corporate,
    Foot
  }
}
</script>

<style>

</style>
