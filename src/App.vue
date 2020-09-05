<template>
  <div id="app">
    <!-- <Nav /> -->
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
// import Nav from "./components/Nav.vue";

export default {
  name: 'App',
  components: {
    HelloWorld,
    // Nav,
  }
}
</script>

<style lang="sass">
@import '~argon-design-system-free/assets/css/argon-design-system.min.css'
@import '~argon-design-system-free/assets/css/font-awesome.css'
@import '~argon-design-system-free/assets/css/nucleo-svg.css'

</style>
