<template>
  <img class="inline-block align-middle pb-8" alt="DivTag logo" src="./assets/divtag.jpeg">
  <!-- TODO: Modify AppHeader component then uncomment the line below -->
<!--  <AppHeader />-->
  <HomePage />
  <AppFooter/>
</template>

<script>
import HomePage from './components/HomePage.vue'
import AppFooter from "@/components/AppFooter";

export default {
  name: 'App',
  components: {
    HomePage,
    AppFooter
  }
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  line-height: 1.5;
  color: #555555;
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