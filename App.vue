<template>
  <z-canvas :views="$options.components"></z-canvas>
</template>
<script>
import home from "/components/home";
import foo from "/components/foo";
import og from "/components/floors/og";
import eg from "/components/floors/eg";

export default {
  components: {
    home,
    eg,
    og,
    foo
  },
  mounted() {
    this.$zircle.setView("home");
  }
};
</script>
<style>
</style>
