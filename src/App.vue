<template>

  <firstApp/>
<headerPart></headerPart>
  <footerNote/>
</template>

<script>
import headerPart from './components/headerPart.vue';
import firstApp from './components/firstApp.vue';
import footerNote from './components/footerNote.vue';
export default {
  // name: 'App',
  components: {
      firstApp,
      headerPart,
      footerNote
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
</style>
