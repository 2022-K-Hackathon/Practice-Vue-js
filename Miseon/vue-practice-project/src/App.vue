<template>
  <div class="container">
    <h4>My First Web App</h4>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {

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
  margin: 0 auto;
}

.container {
  background-color: palevioletred;
  max-width: 600px;
  height: 100vh;

  /* center sort */
  display: block; 
  margin-left: auto;
  margin-right: auto;
}
</style>
