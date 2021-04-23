<template>
  <div>
      <button @click="loudJoke">Generate loud joke</button>
      <br>
      <br>
      <div id="loudJoke_container"></div>
      <br>
  </div>
</template>

<script>
export default {
  name: 'loud-joke'
}
</script>

<style scoped>
#loudJoke_container {
  width: 500px;
  height: 200px;
  background-color: aqua;
}
</style>
