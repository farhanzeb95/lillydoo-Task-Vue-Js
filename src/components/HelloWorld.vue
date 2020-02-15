<template>
  <div class="overlayDiv">
    <h1 class="fontStyle">Dein gratis Testpaket</h1>
    <a href class="btn">Wähle Deine Größe</a>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.overlayDiv {
  align-self: flex-end;
    padding: 2.5rem 1rem 1.5rem 1rem;
    background: rgba(255,255,255,.7);
   margin-left: 65%;
    margin-bottom: 10%;
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
