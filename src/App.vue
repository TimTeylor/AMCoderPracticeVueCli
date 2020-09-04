<template>
  <div id="app">
    <img alt="Vue logo" style="max-width:100%;height:250px;" src="https://www.publicdomainpictures.net/pictures/320000/velka/love-banner-card.png">
    <HelloWorld msg="Я люблю тебя кисик))"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
