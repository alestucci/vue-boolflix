<template>
  <div id="app">
    <bool-header />
    <bool-main />
  </div>
</template>

<script>
import BoolHeader from "./components/BoolHeader.vue";
import BoolMain from "./components/BoolMain.vue";

export default {
  name: "App",
  components: {
    BoolHeader,
    BoolMain,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
