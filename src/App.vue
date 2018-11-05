<template>
  <div id="app">
    <Landing />
    
  </div>
</template>

<script>
import Landing from "./components/Landing";

export default {
  name: "app",
  components: {
    Landing
  }
};
</script>

<style>
#app {
  font-family: "PT Sans", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 10rem;
}
a {
  color: white;
}
body {
  background-image: linear-gradient(
    to right,
    #242423,
    #303230,
    #242423,
    #2b2d2b,
    #242423
  );
}
</style>
