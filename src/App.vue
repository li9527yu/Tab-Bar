<template>
  <div id="app">
    <router-view></router-view>
    <main-tab-bar></main-tab-bar>
  </div>
</template>

<script>
import MainTabBar from './components/MainTabBar'
export default {
  name: 'App',
  components: {
    MainTabBar
  }
}

</script>

<style>
  /* @import "./assets/css/base.css/"; */
  #app{
    margin: 0;
    padding: 0;
  }
</style>
