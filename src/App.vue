<template>
  <div id="app">
    <img class="logo" src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
body,
html {
  margin: 0;
  padding: 0;
  background-color: #fcfcfc;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  padding-right: 25px;
  padding-left: 25px;
}

.logo {
  max-width: 100%;
  width: 220px;
}

@media(min-width: 600px) {
  .logo {
    width: 430px;
  }
}
</style>
