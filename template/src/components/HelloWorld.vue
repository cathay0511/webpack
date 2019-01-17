<template>
  <div class="hello">
    <img src="//pt-starimg.didistatic.com/static/starimg/img/1512125138062YWDdoSWsNBleIjjayOg.png">
    <h2>\{{ msg }}</h2>
    <h5 class="slogan">simple &! common</h5>
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
<style lang="scss" scoped>

$color: #999;

.slogan {
  color: $color;
  font-size: 14px;
}

</style>
