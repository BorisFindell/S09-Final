<template>
  <div id="app">
    <div>
        <router-view/>
    </div>
  </div>


</template>


<script>


export default {
  name: 'App',
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: max-content;
  max-height: 100vh;
  overflow:auto;
}

</style>
