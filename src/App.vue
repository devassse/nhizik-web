<template>
  <nav-bar></nav-bar>
</template>

<script>
import NavBar from './components/NavBar.vue';

export default {
  name: 'App',
  components: {
    NavBar
  }
}
</script>
<style>
  /* Importing Main Stylesheet */
  @import './assets/css/main.scss';
  @import './assets/css/site.min.css';
</style>