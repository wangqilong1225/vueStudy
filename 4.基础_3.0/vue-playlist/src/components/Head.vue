<template>
  <div class="Head">
    <h1>{{ Title }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Head',
  data () {
    return {
      Title: 'This is Head Scope'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.Head{
    background-color:#333;
    padding:0;
    margin:0;
}

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
