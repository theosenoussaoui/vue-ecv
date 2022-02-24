<template>
  <TailwindExample msg="voici avec tailwind" />
  <StyledExample msg="voici avec styled-components" />
  <GridExample/>
  <GridPlacementExample/>
</template>

<script>
import TailwindExample from "./components/TailwindExample.vue";
import StyledExample from "./components/StyledExample/StyledExample.vue";
import GridExample from "@/components/Grid";
import GridPlacementExample from "@/components/GridPlacement";

export default {
  name: "App",
  components: {
    GridPlacementExample,
    GridExample,
    TailwindExample,
    StyledExample,
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
