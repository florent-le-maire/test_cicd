<template>
  <FormConnect></FormConnect>
</template>

<script>
import FormConnect from './components/FormConnect.vue'

export default {
  name: 'App',
  components: {
    FormConnect
  }
}
</script>

<style>
html,
body,
#app{
  height: 100%;
}
body {
  background: -webkit-linear-gradient(aquamarine, blue);
  background: -o-linear-gradient(aquamarine, blue);
  background: -moz-linear-gradient(aquamarine, blue);
  background: linear-gradient(aquamarine, blue);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  display: flex;
  flex-flow: column;
  justify-content: center;
  align-items: center;
}
</style>
