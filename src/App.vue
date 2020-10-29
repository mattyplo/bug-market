<template>
  <div>
    <BugItemCard bugName="Cricket" imageName="cricket" imagePath="assets/cricket.jpeg"/>
    <BugItemCard bugName="Silk Worm"/>
    <BugItemCard bugName="Spiders"/>
  </div>
</template>

<script>
import BugItemCard from './components/BugItemCard.vue'

export default {
  name: 'App',
  components: {
    BugItemCard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
