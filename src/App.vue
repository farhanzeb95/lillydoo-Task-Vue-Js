<template>
  <div id="appHeader">
  <div v-componenet="Header">
   <HelloWorld/>
</div>
    <Container></Container>


  </div>
</template>


<script>
export default {
  name:'App'
}
</script>

<style>

</style>
<script>
import Header from "./components/Header.vue"
import HelloWorld from "./components/HelloWorld.vue";
import Container from "./components/Container.vue";
import FirstContainer from "./components/FirstContainer.vue"

export default {
  name: "App",
  components: {
    Header,
    HelloWorld,
    Container,
    FirstContainer
  }
};
</script>

<style>
#appHeader {
  width: 100%;
  height: 30rem;
  background-image: url("./assets/images/header-trialbox-desktop.jpg");
}
</style>
