<template>
  <div class="hello">
    <h1>关于我</h1>
    <h2>{{ name }}</h2>
  </div>
</template>

<script>
export default {
  name: 'About',
  data () {
    return {
      msg: '天外飞熊'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
