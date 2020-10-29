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
.fa-user:before {
  content: "\f007";
}
.main {
  height: 100%;
  padding: 3em 2em;
  text-align: center;
  overflow: auto;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #4e4a46;
  text-decoration: none;

  &:hover,
  &:focus {
    color: #7e628f;
  }
}
h1 {
  font-weight: 800;
  font-size: 3.75em;
}
h6 {
  font-size: 15px;
  color: gray;
}
p {
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bold;
}
</style>
