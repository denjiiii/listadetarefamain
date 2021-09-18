<template>
  <header>
    <h1>{{ valor }}</h1>
  </header>
</template>

<script>
export default {
  props: ["valor"],
};
</script>

<style>
header {
  background-color: aquamarine;
  height: 60px;
  width: 100%;
  position: fixed;
  top: 0px;
  text-align: center;
  color: aliceblue;
}
</style>