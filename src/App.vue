<template>
  <div>
    <h1>Hello World</h1>
    <h2>{{ cheese }}</h2>
    <HelloWorld :cheese="cheese"/>
    <button @click="handleClick">Click Me</button>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld"
export default {
  name: 'App',
  data() {
    return {
      cheese: "gouda"
    }
  },
  components: {HelloWorld},
  methods: {
    handleClick() {
      this.cheese = "munster"
    }
  },
}
</script>

<style>
h1 {
  color: green;
}
</style>