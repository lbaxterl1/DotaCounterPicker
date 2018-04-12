<template>
  <div id="app">
    <div class="leftHero">
      <HelloWorld/>
    </div>

    <div class="rightHero">
      <HelloWorld/>
    </div>
   
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
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

.leftHero, .rightHero {
  width: 20%;
}

.heroList li {
  display: block;
}

.leftHero {
  float: left;
}

.rightHero {
  float: right;
}
</style>
