<template>
  <div id="app">
    <h1>Calculator</h1>
    <calculator />
  </div>
</template>

<script>
import Calculator from './main/Calculator'
export default {
  components: { Calculator }

}
</script>

<style>
* {
  font-family: "RobotoMono", monospace;
}

body {
  margin: 0;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;

  background: aliceblue;
}

</style>