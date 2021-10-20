<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <base-component-a :msg="msg" />
    <base-component-b :msg="msg" />
    <base-component-c :msg="msg" />
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      msg: "Welcome to Your Vue.js App",
    };
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
