<template>
  <div id="app">
    <h1>Imported on template</h1>
    <img src="./assets/icons/facebook.svg" width="200" height="200">

    <h1>Imported on styles</h1>
    <div class="twitter-logo">
    </div>
  </div>
</template>

<script>

export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}

.twitter-logo {
  width: 200px;
  height: 200px;
  background: url('./assets/icons/twitter.svg') no-repeat;
  background-size: contain;
}
</style>
