<template>
  <el-page-header content="detail" @back="goBack" />
  <img alt="Vue logo" src="./assets/logo.png" />
</template>
<script setup>
const goBack = () => {
  console.log("go back");
};
</script>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
