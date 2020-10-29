<template>
  <div class="main">
    <h1>
      <a href="https://github.com/">Vue-Toggle</a>
    </h1>

    <!-- Toggle -->
    <label class="switch">
      <input type="checkbox" />
      <span class="slider round"></span>
      <h6>Off (checked)</h6>
    </label>

    <label class="switch">
      <input checked type="checkbox" />
      <span class="slider round"></span>
      <h6>On (checked)</h6>
    </label>

    <!-- Disabled toggle -->
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
    <!-- Toggle without background color -->
    <label class="switch">
      <input checked type="checkbox" />
      <span class="slider round w-color"></span>
      <h6>Custom toggle</h6>
    </label>

    <!-- Toggle Rolling  with icons-->
    <label class="switch">
      <input checked type="checkbox" />
      <span class="slider round icon"></span>
      <h6>Toggle & icons</h6>
    </label>
  </div>
</template>

<script>
export default {
  name: "Toggle"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
