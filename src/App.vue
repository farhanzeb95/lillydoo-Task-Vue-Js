<template>
  <div id="app">
    <Header>
      <OverlayDiv />
    </Header>
    <Container />
    <FirstContainer />
    <SecondContainer />
    <Footer />
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style></style>
<script>
import Header from "./components/Header.vue";
import OverlayDiv from "./components/OverlayDiv";
import Container from "./components/Container.vue";
import FirstContainer from "./components/FirstContainer.vue";
import SecondContainer from "./components/SecondContainer";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    OverlayDiv,
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
body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji",
    "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #212529;
  text-align: left;
  background-color: #fff;
}
</style>
