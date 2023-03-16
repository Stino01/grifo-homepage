<template>
  <div id="app">
    <HeaderFixed />
    <HeroComponent />
    <CarouselVue/>
    <ServiceComponent/>
    <FactoryComponent/>
    <PortfolioComponent/>
    <FormComponent/>
    <FooterComponent/>
  </div>
</template>

<script>

import HeaderFixed from './components/Head.vue'
import HeroComponent from './components/HeroComponent.vue'
import ServiceComponent from './components/ServiceComponent.vue'
import CarouselVue from './components/CarouselComponent.vue'
import FactoryComponent from './components/FactoryComponent.vue'
import PortfolioComponent from './components/PortfolioComponent.vue'
import FormComponent from './components/FormComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderFixed,
    HeroComponent,
    CarouselVue,
    ServiceComponent,
    FactoryComponent,
    PortfolioComponent,
    FormComponent,
    FooterComponent
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
