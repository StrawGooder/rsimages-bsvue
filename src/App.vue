<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <!-- <rsImageManagePlane/> -->
  <MainLyt></MainLyt>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import rsImageManagePlane from './pages/rsImageManagePlane.vue'
import MainLyt from "./layouts/mainLyt.vue"

export default {
  name: 'App',
  components: {
    MainLyt
  }
};
</script>

<style>

@import '../node_modules/bootstrap/dist/css/bootstrap.css';
@import '../node_modules/bootstrap-vue/dist/bootstrap-vue.css';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
