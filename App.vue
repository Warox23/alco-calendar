<template>
  <div id="app">
    <calendar />
  </div>
</template>

<script>
import calendar from "./components/calendar";

export default {
  name: "app",
  components: {
    calendar: calendar
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
