<template>
  <div class="home-container">
    <h1>{{ msg }}</h1>
    <h2>Seafood consulting and brand development</h2>
    <p>We are under construction. Please come back soon!</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to PearlOceans.com'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
h1 {
  margin-bottom: 0;
}
h2 {
  margin-top: 0;
  margin-bottom: 50px;
  font-size: 22px;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
