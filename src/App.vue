<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>

export default {
};
</script>

<style lang="scss">
@import "../public/assets/main.scss";
@import "node_modules/bootstrap/scss/bootstrap";
@import "node_modules/bootstrap-vue/src/index.scss";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.example-var {
  color: $color__button;
}
</style>
