<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <my-component first="Your" last="Name"></my-component>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import { MyComponent } from "vue-library";
import { defineComponent } from 'vue';

export default defineComponent({
  name: "App",
  components: {
    HelloWorld,
    MyComponent,
  },
});
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
