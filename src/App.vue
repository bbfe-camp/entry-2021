<template>
  <div id="app">
    <img alt="BBFE logo" width="160" src="./assets/bbfe-logo.png">
    <introduce/>
  </div>
</template>

<script>
import introduce from './components/introduce.vue'

export default {
  name: 'app',
  components: {
    introduce
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
*,::after,::before {
    box-sizing: border-box
}
a {
    outline: 0;
    text-decoration: none;
    color: #333333;
}

a:hover {
    outline: 0;
    text-decoration: none;
    color: #636fe2;
}

</style>
