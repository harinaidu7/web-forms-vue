<template>
  <Signupform/>
</template>

<script>
import Signupform from "./components/Signupform.vue";


export default {
  name: 'App',
  components: {
    Signupform
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
body{
  background: #eee;
  margin: 0;
}
</style>
