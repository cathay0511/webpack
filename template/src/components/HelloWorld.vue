<template>
  <div class="hello">
    <img src="//pt-starimg.didistatic.com/static/starimg/img/1512125138062YWDdoSWsNBleIjjayOg.png">
    <h1>\{{ msg }}</h1>
    <h2>simple &! common</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'hi, star component!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  text-align: center;
}
</style>
