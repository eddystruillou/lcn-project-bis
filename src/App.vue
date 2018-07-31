<template>
  <div id="app">
    <Player />
  </div>
</template>

<script>
import Player from './components/Player.vue'

export default {
  name: 'app',
  components: {
    Player
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
