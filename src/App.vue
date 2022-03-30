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
  background: -webkit-linear-gradient(#3871ec, blue);
  background: -o-linear-gradient(#3871ec, blue);
  background: -moz-linear-gradient(#3871ec, blue);
  background: linear-gradient(#3871ec, blue);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  display: flex;
  flex-flow: column;
  justify-content: center;
  align-items: center;
}
</style>
