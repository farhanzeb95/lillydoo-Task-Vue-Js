<template>
  <div class="overlayDiv">
    <h1 class="fontStyle">Dein gratis Testpaket</h1>
    <a href class="btn">Wähle Deine Größe</a>
  </div>
</template>

<script>
export default {
  name: "FirstContainer"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.overlayDiv {
  background-color: rgba(255, 255, 255, 0.7);
  height: 10rem;
  width: auto;
  float: right;
  margin-top: 140px;
  margin-right: 50px;
  padding: 40px 40px 24px;
}
.fontStyle {
  font-family: Museo-300, Helvetica, Roboto, Arial, sans-serif;
  font-size: 2.625rem;
  text-align-last: center;
  font-style: normal;
  font-weight: 300;
  text-rendering: optimizeLegibility;
}
.btn {
  background-color: #00afab;
  text-align-last: center;

  width: 18.1rem;
  height: 3rem;
  color: aliceblue;
  font-family: Helvetica, Roboto, Arial, sans-serif;
  text-decoration: none;
  margin-left: auto;
  margin-right: auto;
  display: block;
}

.btn:hover {
  opacity: 0.5;
}
</style>
