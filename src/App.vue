<template>
  <div id="app">
    <Exercise1/>
    <br/>
    <Exercise2/>
    <br/>
    <Exercise3/>
    <br/>
    <Exercise4/>
    <br/>
    <Exercise5/>
  </div>
</template>

<script>

import Exercise1 from "./components/Exercise1.vue";
import Exercise2 from "./components/Exercise2.vue";
import Exercise3 from "./components/Exercise3.vue";
import Exercise4 from "./components/Exercise4.vue";
import Exercise5 from "./components/Exercise5.vue";
export default {
  name: "app",
  components: {
      Exercise1,
      Exercise2,
      Exercise3,
      Exercise4,
      Exercise5
  }
};
</script>

<style>
#app {
  /*font-family: "Avenir", Helvetica, Arial, sans-serif;*/
  /*-webkit-font-smoothing: antialiased;*/
  /*-moz-osx-font-smoothing: grayscale;*/
  /*text-align: center;*/
  /*color: #2c3e50;*/
  /*margin-top: 60px;*/
}
</style>
