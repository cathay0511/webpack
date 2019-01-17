<template>
  <div class="hello">
    <h5 class="slogan">\{{msg}}</h5>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: {
      type: String
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

$color: #999;

.hello {

  .slogan {
    color: $color;
    font-size: 14px;
  }
}

</style>
