<template>
  <div>
    <button id="newJoke" @click="newJoke">Generate random joke</button>
    <br />
    <br />
    <div id="newJoke_container"></div>
    <br />
  </div>
</template>

<script>
export default {
  name: 'joke-button'
  data: newJoke() {
      return {
      }
  },
}
</script>

<style scoped>
#newJoke_container {
  width: 500px;
  height: 200px;
  background-color: lime;
}
</style>
