<template>
  <div id="app">
    <HelloWorld />
    <div class="container-fluid mt-2">
      <Card />
    </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Card from "./components/Card.vue";

export default {
  name: "app",
  components: {
    HelloWorld,
    Card
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
