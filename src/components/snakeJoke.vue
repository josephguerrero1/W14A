<template>
  <div>
      <button @click="snakeJoke">Generate snake joke</button>
      <br>
      <br>
      <div id="snakeJoke_container"></div>
      <br>
  </div>
</template>

<script>
export default {
  name: 'snake-joke'
}
</script>

<style scoped>
#snakeJoke_container {
  width: 500px;
  height: 200px;
  background-color: crimson;
}
</style>
