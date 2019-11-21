<template>
  <div id="app">
    <img src="./assets/logo.png">

    <Button type="primary" @click="btn_click">Show Notice</Button>

    <Button type="info" to="/">Home</Button>
    <Button type="info" to="/about">About</Button>
    <router-view/>
  </div>
</template>

<script>
export default {
    name: 'App',

    methods: {
        btn_click: function() {
            this.$Notice.info({title: "Title", desc: "this is iView Notice"})
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
  margin: 0px;
  padding:0px;
    -border: 1px solid rgb(74, 112, 129);
}
</style>
