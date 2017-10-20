
<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'app',
  data(){
    return {
      my: 'First variable, bitch'
    }
  },
  components: {
    HelloWorld
  }
}
</script>


<template>
  <div id="app">
    <img src="./assets/logo.png">
    {{my}}
    <HelloWorld/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
