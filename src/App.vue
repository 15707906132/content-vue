<template>
  <div>
    <!-- <img src="./assets/logo.png"> -->
    <!-- <v-hello></v-hello> -->
    <!-- <router-view></router-view> -->
    <v-header></v-header>
    <v-navs></v-navs>
  </div>
</template>

<script>
// import vHello from './components/Hello.vue'
import vHeader from './components/header/header.vue'
import vNavs from './components/navs/navs.vue'

export default {
  name: 'app',
  components: {vHeader, vNavs}
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
</style>
