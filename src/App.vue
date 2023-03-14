<template>
  <div id="app">
    <HeaderFixed />
    <HeroComponent />
  </div>
</template>

<script>
import HeaderFixed from './components/Head.vue'
import HeroComponent from './components/HeroComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderFixed,
    HeroComponent
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
