<template>
  <div>
    <joke-button></joke-button>
    <loud-joke></loud-joke>
    <snake-joke></snake-joke>
    <normal-joke></normal-joke>
  </div>
</template>

<script>
import jokeButton from './components/jokeButton.vue'
import normalJoke from './components/normalJoke'
import snakeJoke from './components/snakeJoke.vue'
import loudJoke from './components/loudJoke.vue'

export default {
  name: 'App',
  components: {
    jokeButton,
    normalJoke,
    snakeJoke,
    loudJoke
  }
}
</script>

<style>
</style>
