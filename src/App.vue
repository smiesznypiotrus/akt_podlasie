<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.full-height {
  min-height: 100vh;
}

.full-width {
  min-width: 100vh;
}

html {
    overflow-x: hidden;
    width: 100%;
    min-width: 300px;
}

body {
    overflow-x: hidden;
    width: 100%
}
</style>
