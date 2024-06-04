<template>
  <ParallaxWebsite />
</template>

<script>
import ParallaxWebsite from "./components/ParallaxWebsite.vue";

export default {
  name: "App",
  components: {
    ParallaxWebsite,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap");
#app {
  font-family: "Open Sans", Arial, Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
