<template>
  <nav-bar></nav-bar>
  <main-content></main-content>
  <main-footer></main-footer>
</template>

<script>
import NavBar from './components/NavBar.vue'
import MainContent from './components/MainContent.vue'
import MainFooter from './components/MainFooter.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    MainContent,
    MainFooter
  }
}
</script>
<style>
  /* Importing Main Stylesheet */
  @import './assets/css/main.scss';
  @import './assets/css/style.min.css';
</style>