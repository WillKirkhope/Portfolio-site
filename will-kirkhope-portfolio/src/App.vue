<template>
  <div id="app">
    <Header />
    <Home />
  </div>
</template>

<script>
import Header from './components/Header'
import Home from './components/Home'
export default {
  name: 'App',
  components: {
    Header,
    Home
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Rubik:300i');

#app {
  font-family: 'Rubik', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
