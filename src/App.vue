<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
  import Vue from 'vue'
  import HelloWorld from './components/HelloWorld.vue'

  export default Vue.extend({
    name: 'App',
    components: {
      HelloWorld
    }
  })
</script>

<style>
</style>
