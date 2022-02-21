<template>
  <TailwindExample msg="voici avec tailwind" />
</template>

<script>
import TailwindExample from "./components/TailwindExample.vue";

export default {
  name: "App",
  components: {
    TailwindExample,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
