<template>
  <div id="app">
    <div class="home">
      <div class="container">
        <div class="title">Auktoberfest is comming...</div>
        <Counter class="counter"/>
        <div>
          <iframe src="https://giphy.com/embed/e6TR9n00dL3JS" frameBorder="0"></iframe>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Counter from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    Counter
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.home {
  text-align: center;
}

.container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.title {
  font-size: 2em;
  font-weight: bold;
  margin-bottom: 1em;
}

.counter {
  margin: 1em;
}

iframe {
  margin-top: 1em;
}
</style>
