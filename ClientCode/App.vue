<template>
  <div id="app">
    <p>Hello World from Vue!</p>
    Your name? <input v-model="name" type="text"/>

    <div v-if="name ">Hi, {{name}}</div>
  </div>
</template>

<script>

export default {
  name: 'app',
  components: {
  },
  data () {
    return {
      name: null
    }
  }
};
</script>

<style>
</style>
