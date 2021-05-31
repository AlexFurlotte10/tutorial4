<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Header msg="Welcome to Your Vue.js App"/>
    <Profile msg="hello"/>
    <Footer msg="Hello"/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Profile from './components/Profile.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Profile,
    Footer
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
