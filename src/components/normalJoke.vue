<template>
  <div>
      <button @click="normalJoke">Generate normal joke</button>
      <br>
      <br>
      <div id="normalJoke_container"></div>
      <br>
  </div>
</template>

<script>
export default {
  name: 'normal-joke'
}
</script>

<style scoped>
#normalJoke_container {
  width: 500px;
  height: 200px;
  background-color: khaki;
}
</style>
