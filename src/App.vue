<template>
  <div id="app">
    <router-view />
  </div>
</template>
<script>
export default {
  name: "App",
  metaInfo() {
    return {
      title: "Vue-Toggle"
    };
  }
};
</script>

<style src="./assets/styles/main.css"></style>
