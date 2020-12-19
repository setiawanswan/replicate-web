<template>
  <div id="app">
    <Navbar msg="Ini Navbar" />
    <Header/>
    <Information />
    <Insight />
    <Corporate />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Header from './components/Header.vue'
import Information from './components/Information.vue'
import Insight from './components/Insight.vue'
import Corporate from './components/Corporate.vue'

export default {
  name: 'App',
  components: {
    Header,
    Navbar,
    Information,
    Insight,
    Corporate
  }
}
</script>

<style>

</style>
