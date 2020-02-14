<template>
  <div id="appHeader">
   
    <HelloWorld msg="Welcome to Your Vue.js App"/>
      <div id="pkgTest">

      </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#appHeader {
  width: 100%;
  height: 30rem;
  background-image: url('./assets/images/header-trialbox-desktop.jpg')
}
</style>
