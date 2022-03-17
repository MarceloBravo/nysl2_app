<template>
  <div id="app">
    <router-view/>
    <NavbarComponent/>
  </div>
</template>

<script>
  import NavbarComponent from './components/Navbar/NavbarComponent.vue';

  export default {
    name: 'App',

    components: {
      NavbarComponent
    }
  }
</script>

<style>
  @import './styles/App.scss';
</style>
