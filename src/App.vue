<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <FieldComponent :data = "FieldData"/>
  </div>
</template>

<script>
import FieldComponent from './components/FieldComponent.vue'

export default {
  name: 'App',
  components: {
    FieldComponent
  },
  data(){
    return{
      FieldData: "Примерный текст для вывода",
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
