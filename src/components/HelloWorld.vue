<template>
  <div class="hello">
    <h1>Hello la promo Ynov !</h1>
    <h3>Bienvenue sur Ynov Songs :)</h3>
    <Liste></Liste>
  </div>
</template>


<script>
import Liste from "./Liste"; // 1 import
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  components: {
    Liste, // 2 use
  },
};
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
</style>
