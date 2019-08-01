<template>
  <Rating />
</template>

<script>
import Rating from './components/Rating'


export default {
  name: 'app',
  components: {
    Rating
  }
}
</script>

<style lang="scss">
* {
  margin: 0px;
  padding: 0px;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
