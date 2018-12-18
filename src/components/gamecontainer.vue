<template>
  <div>
    <header>
      <div class="row">
         <h1>Card Battle！</h1>
         <section id="game" class="row">
          <start-scene></start-scene>
        </section>
      </div>
    </header>
    <section class="how-to-play">
      <h2>玩法介绍</h2>
      <p>选择任意一张牌，然后观看点数的pk结果</p>
    </section>
    <footer>
      <p>给我打个赏把！</p>
      <img id="payme" src="../../static/payme.jpg">
    </footer>
  </div>
</template>

<script>
  import StartScene from './startscenecomponent'
  export default {
    components: {
      StartScene
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #game {
    wdith: 480px;
    height:600px;
    border-radius: 8px;
    overflow: hidden;
  }

  .scene {
    width: 100%;
    height: 100%;
    position: absolute;
    overflow: hidden;
    border-radius: 8px;
    transition: all.3s ease-out;

  }

  #payme {
    width:240px;
    height: 256px;
  }
</style>
