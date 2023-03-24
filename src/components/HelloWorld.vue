<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide 
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li>babel</li>
      <li>eslint</li>
    </ul>
    <h3>Essential Links</h3>
    <div class="ad" >adadada</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
.ad{
  width: 150px;
  height: 50px;
  background-color: #CCC;
  border :10;
  position: fixed;
  right: 20px;
  bottom: 20px;

}
</style>
