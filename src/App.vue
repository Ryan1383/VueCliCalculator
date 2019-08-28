<template>
  <div id="app">
    <Calculator />
  </div>
</template>

<script>
import Calculator from "./components/Calculator";
export default {
  name: "app",
  components: {
    Calculator
  }
};
</script>

<style>
* {
  box-sizing: border-box;
}

body {
  text-align: center;
}
</style>
