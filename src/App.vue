<template>
  <div id="app">
    <AppTaskShow></AppTaskShow>
    <AppTaskEntry></AppTaskEntry>
    <AppTaskFilter></AppTaskFilter>
  </div>
</template>

<script>
import AppTaskEntry from "@/components/AppTaskEntry.vue";
import AppTaskFilter from "@/components/AppTaskFilter.vue";
import AppTaskShow from "@/components/AppTaskShow.vue";

export default {
  name: "App",
  components: {
    AppTaskEntry,
    AppTaskFilter,
    AppTaskShow,
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
