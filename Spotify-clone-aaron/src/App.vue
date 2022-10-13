<template>
  <div id="app">
    <TopNav></TopNav>
    <LeftNav></LeftNav>
    <RightNav></RightNav>
    <BottomNav></BottomNav>
    <MainPage></MainPage>
  </div>
</template>

<script setup>
import { ref } from 'vue'
import TopNav from './components/TopNav.vue'
import LeftNav from './components/LeftNav.vue'
import RightNav from './components/RightNav.vue'
import BottomNav from './components/BottomNav.vue'
import MainPage from './components/MainPage.vue'

</script>

<style scoped>
#app {
}

#main {
  width: 100vw;
  height: 100vh;
}

header {
  line-height: 1.5;
  max-height: 100vh;
}
</style>
