<template>
  <div class="main">
    <h1>
      <a href="https://github.com/mahazz/Vue-Toggle" v-t="'toggle_header'"></a>
    </h1>
    <!-- OFF | ON -->
    <ToggleOff />
    <ToggleOn />

    <!-- Disabled toggle -->
    <DisabledToggle />

    <!-- Custom Toggler -->
    <ToggleCustom />

    <!-- Toggle Rolling  with icons-->
    <ToggleIcon />
  </div>
</template>

<script>
import ToggleOff from "./Toggle/ToggleOff";
import ToggleOn from "./Toggle/ToggleOn";
import DisabledToggle from "./Toggle/DisabledToggle";
import ToggleCustom from "./Toggle/ToggleCustom";
import ToggleIcon from "./Toggle/ToggleIcon";

export default {
  name: "Toggle",
  components: {
    ToggleOff,
    ToggleOn,
    DisabledToggle,
    ToggleCustom,
    ToggleIcon
  },
  message: {
    toggle_header: "Vue-Toggle",
    de: "Hallo du, Vuejs"
  },
  currentLocale: "en",
  locales: [
    { id: "en", name: "English" },
    { id: "de", name: "Deutsch" }
  ]
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
