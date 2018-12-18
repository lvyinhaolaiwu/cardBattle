<template>
  <div id="app">
    <!--
    <img src="./assets/logo.png">
    -->
    <game-container></game-container>
    <!--
    <router-view/>
    -->
  </div>
</template>

<script>
  import GameContainer from './components/gamecontainer'
export default {
  components: {
    GameContainer
  },
  name: 'App'
}
</script>

<style>
  /**
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
  **/
</style>
