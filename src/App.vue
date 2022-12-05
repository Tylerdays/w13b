<template>
  <div id="app">
    <tweetsComp/>
  </div>
  
</template>

<script>
import tweetsComp from '@/components/tweetsComp.vue';

export default {
  name: 'App',
  components: {
    tweetsComp
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
