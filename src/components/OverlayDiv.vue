<template>
  <div class="overlayDiv">
    <h1 class="fontStyle">Entdecke unsere Hautfreundlichkeit</h1>
    <button href class="button btn-lg, btn-md, btn-sm, btn-xs, btn-xxl">Wähle Deine Größe</button>
  </div>
</template>

<script>
export default {
  name: "OverlayDiv"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Roboto+Condensed');
.overlayDiv {
/*
  padding: 2.5rem 1rem 1.5rem 1rem;
  background: rgba(255, 255, 255, 0.7);
  margin-bottom: 10%;
  height: 50%;
  margin-top: 15%; */
    background: rgba(255, 255, 255, 0.7);
    height: 50%;
      margin-top: 10%;
      padding: 20px;
}
.fontStyle {
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  font-size: 5vh;
  text-align-last: center;
  font-style: normal;
  font-weight: 300;
  text-rendering: optimizeLegibility;
      text-align: center;
}
.button {
  background-color: #00afab;
  text-align-last: center;
  width: 18.1rem;
  height: 3rem;
  color: #fff;
  font-family: Helvetica, Roboto, Arial, sans-serif;
  text-decoration: none;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  justify-content: center;
  border-radius: inherit;
  border: none;
}
button:hover {
  opacity: 0.5;
}

@media only screen and (max-width: 600px) {
 .overlayDiv {
      margin-top: 100%;
  }
}



</style>
