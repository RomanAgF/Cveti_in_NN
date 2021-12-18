<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Links msg="Hello Vue 3 in CodeSandbox!" />
</template>

<script>
import Links from "./components/Links.vue";
export default {
  name: "App",
  components: {
    Links: Links,
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
