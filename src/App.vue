<template>
  <img alt="Vue logo" src="./assets/divtag.jpeg">
  <HomePage />
  <Footer/>
</template>

<script>
import HomePage from './components/HomePage.vue'
import Footer from "@/components/Footer";

export default {
  name: 'App',
  components: {
    HomePage,
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

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>