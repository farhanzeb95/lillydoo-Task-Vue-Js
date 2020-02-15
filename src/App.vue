<template>
<div id="app">
  <Header>
  <HelloWorld/>
  </Header>
  <Container/>
  <FirstContainer/>
  <SecondContainer/>
  <Footer/>
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
import Container from "./components/Container.vue"
import FirstContainer from "./components/FirstContainer.vue";
import SecondContainer from "./components/SecondContainer";
import Footer from "./components/Footer.vue"


export default {
  name: "App",
  components: {
    Header,
    HelloWorld,
    Container,
    FirstContainer,
    SecondContainer,
    Footer
  }
};
</script>

<style>
#app {
  width: 100%;
  height: auto;
}
</style>
