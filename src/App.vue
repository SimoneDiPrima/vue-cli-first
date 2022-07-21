<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->

    <MyHeader/>
    <JumboImage/>
  </div>
</template>

<script>
import MyHeader from './components/TitleComponent.vue'
import JumboImage from './components/JumbotronComponent.vue'
export default {
  name: 'App',
  components: {
    MyHeader,
    JumboImage
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 60px;
}
</style>
