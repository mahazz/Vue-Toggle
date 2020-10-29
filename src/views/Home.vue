<template>
  <div class="home">
    <Toggle />
  </div>
</template>

<script>
// @ is an alias to /src
import Toggle from "@/components/Toggle.vue";

export default {
  name: "Home",
  components: {
    Toggle,
  },
};
</script>
