<template>
  <div id="app">
    <main></main>
  </div>
</template>

<script>
import Panel from "./components/Panel.vue";
import InputForm from "./components/InputForm.vue";
import Result from "./components/Result";
import { calcTaxes } from "./calc.js";

export default {
  name: "app",
  components: {
    Panel,
    InputForm,
    Result
  }
};
</script>

<style lang="scss" src="./assets/styles/App.scss"/>
