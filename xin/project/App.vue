<template>
  <div id="app">
    <h1 v-text="title"></h1>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      title: 'this is a todo list'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>