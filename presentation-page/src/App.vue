<template>
  <div id="app">
    <About/>
    <Skill/>
    <Experience/>
  </div>
</template>

<script>
import About from './components/About'
import Skill from './components/Skill'
import Experience from './components/Experience'

export default {
  name: 'app',
  components: {
    About,
    Skill,
    Experience
  }
}
</script>

<style>
#app {
}
</style>
