<template>
  <div id="app">
    <HeaderFixed />
  </div>
</template>

<script>
import HeaderFixed from './components/Head.vue'

export default {
  name: 'App',
  components: {
    HeaderFixed
  }
}
</script>

<style lang="scss">
:root {
  --main-color:#FFFFFF;
  --secondary-color:#B1252C;
}

#app {
  font-family: cairo, sans-serif;
}
</style>
