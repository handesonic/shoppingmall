<template>
  <div id="app">
    <main-tab-bar/>
    <router-view></router-view>
  </div>
</template>

<script>
import MainTabBar from 'components/content/mainTabBar/MainTabBar'

export default {
  name: 'App',
  components: {
    MainTabBar
  }
}
</script>

<style>
  @import url(assets/css/base.css);
</style>
