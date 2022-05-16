<template>
  <div id="app">
    <MyTitle />
    <JumboHero />
  </div>
</template>

<script>
import MyTitle from "./components/MyTitle.vue";
import JumboHero from "./components/JumboHero";

export default {
  name: "App",
  components: {
    MyTitle,
    JumboHero,
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 30px;
}
</style>
