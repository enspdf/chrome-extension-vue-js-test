<template>
  <div id="app">
    <img src="https://avatars3.githubusercontent.com/u/8334660"></img>
    <h1>{{ msg }}</h1>
    <a href="#!" @click="funcion()">Ejecutar Función</a>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Shackox Manzza'
    }
  },
  methods: {
    funcion () {
      this.msg = 'Función ejecutada'
    }
  }
}
</script>

<style>
body {
  background-color: #001835;
  width: 400px;
  height: 250px;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #98CD48;
  margin-top: 60px;
}
h1, h2 {
  font-weight: normal;
}
a {
  color: #FFF;
}
</style>
