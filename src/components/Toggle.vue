<template>
  <div class="main">
    <h1>
      <a href="https://github.com/mahazz/Vue-Toggle"
        >Vue-Toggle
        <i class="toggle fa-github-square"></i>
      </a>
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
    <p class="dev-footer">
      Developed by
      <a href="https://github.com/mahazz/">Maha Alzahrani</a>
    </p>
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
    ToggleIcon,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
