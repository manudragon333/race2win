<template>
  <HomePage msg="Welcome to Your Vue.js App" />
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import HomePage from "./components/HomePage.vue";

export default {
  name: "App",
  components: {
    HomePage,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 2px;
}
.box {
  border: 1px solid #ccc;
  border-radius: 8px;
  padding: 8px;
}
.flex {
  display: flex;
  justify-content: space-evenly;
}
.jc-fs {
  justify-content: flex-start;
}
.jc-fe {
  justify-content: flex-end;
}
.jc-c {
  justify-content: center;
}
.jc-sa {
  justify-content: space-around;
}
.jc-sb {
  justify-content: space-between;
}
.flex-vertical {
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
}
</style>
