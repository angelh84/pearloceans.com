<template>
  <div class="home-container">
    <h1>{{ msg }}</h1>
    <h2>Seafood consulting and brand development</h2>
    <p class="construction-text">We are under construction. Please come back soon!</p>
    <p>Meghan Russell, Founder<br>meghan@pearloceans.com<br>+1 (727) 373-8050<br><a href="https://www.linkedin.com/in/meghan-russell-6824b1a8/" target="_blank">LinkedIn</a> &bull; <a href="https://www.instagram.com/pearloceansseafood/" target="_blank">Instagram</a></p>
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
<style lang="scss" scoped>
h1, h2 {
  font-weight: normal;
}
h1 {
  margin-bottom: 0;
}
h2 {
  margin-top: 0;
  margin-bottom: 5px;
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
  color: #20a1f3;
}
.construction-text {
  margin-bottom: 40px;
}
</style>
