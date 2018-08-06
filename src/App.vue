<template>
  <div id="app">
    <Date />
    <Player /> 
  </div>
</template>

<script>
import Player from './components/Player.vue'
import Date from './components/Date.vue'

export default {
  name: 'app',
  components: {
    Player,
    Date
  }
}
</script>

<style lang="less">
#app {
  background-color: black;
  width: 99vw;
  height: 98vh;
}
</style>
