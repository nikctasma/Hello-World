<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/world.gif" width="250" height="260">
    <HelloWorld :msg="message"/>
    <input type="text" v-model="message" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
export default {
  name: 'app',
  components: {
    HelloWorld
  },
  data(){
    return {
      message: 'Hello World!'
    }
  }

}
</script>

// styles omitted

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
