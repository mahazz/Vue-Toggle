<template>
  <div class="disabled-toggle">
    <label class="switch">
      <input checked disabled type="checkbox" />
      <span class="slider round"></span>
      <h6>Off (disabled)</h6>
    </label>
    <label class="switch">
      <input disabled type="checkbox" />
      <span class="slider round"></span>
      <h6>On (disabled)</h6>
    </label>
  </div>
</template>

<script>
export default {
  name: "Disabledtoggle"
};
</script>

<style lang="scss" scoped>
</style>