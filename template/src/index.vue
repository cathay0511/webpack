<template>
  <div id="star">
    <img src="//pt-starimg.didistatic.com/static/starimg/img/1512125138062YWDdoSWsNBleIjjayOg.png">
    <h2>{{ title }}</h2>
    {{#router}}
    <router-view/>
    {{else}}
    <HelloWorld msg="simple &! common"/>
    {{/router}}
  </div>
</template>

<script>
{{#unless router}}
import HelloWorld from './components/HelloWorld'

{{/unless}}
export default {
  name: 'StarComponent'{{#router}}{{else}},
  components: {
    HelloWorld
  }{{/router}},
  props: {
    title: {
      type: String,
      default () {
        return 'hi, star component!'
      }
    }
  }
}
</script>

<style lang="scss" scoped>

.root {
  margin-top: 60px;
  text-align: center;
}

</style>
