<template>
  <label class="switch">
    <input checked type="checkbox" />
    <span class="slider round icon"></span>
    <h6>Toggle & icons</h6>
  </label>
</template>

<script>
export default {
  name: "Toggleicon",
  data() {},
  message: {
    en: "Hello you, Vue.js!",
    de: "Hallo du, Vuejs"
  },
  currentLocale: "en",
  locales: [
    { id: "en", name: "English" },
    { id: "de", name: "Deutsch" }
  ]
};
</script>

<style lang="scss" scoped>
</style>