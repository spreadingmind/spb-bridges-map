<template>
  <div id="app">
    <google-map/>
  </div>
</template>


<script>
import GoogleMap from "./components/GoogleMap";

export default {
  name: "Bridge Maps",
  components: {
    GoogleMap
  }
};
</script>



<style>
@import url("https://fonts.googleapis.com/css?family=Proza+Libre");
@import url("https://fonts.googleapis.com/css?family=Lobster");
@import url("https://fonts.googleapis.com/css?family=Lora");

h1 {
  font-family: "Lobster", cursive;
  color: #2c3e50;
  font-weight: 500;
  font-size: 55pt;
  margin: 0;
  padding: 0;
}

h5 {
  font-family: "Lora", serif;
  color: #68666d;
  font-size: 10pt;
  margin: 1;
  padding: 1;
}

button {
  margin-top: 10;
  font-family: "Lora", serif;
  font-size: 10pt;
  margin: 10;
}

#app {
  font-family: "Lora", serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
