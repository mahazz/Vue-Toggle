<template>
  <div id="app">
    <Toggle />
    <router-view />
  </div>
</template>
<script>
import Toggle from "./components/Toggle";

export default {
  name: "App",
  metaInfo() {
    return {
      title: "Vue-Toggle"
    };
  },
  components: {
    Toggle
  }
};
</script>

<style src="./assets/styles/main.css"></style>
