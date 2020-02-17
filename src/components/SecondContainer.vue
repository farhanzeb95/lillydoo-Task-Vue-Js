<template>
  <div class="secondContainer">
    <h2 class="topText">Dein Testpaket enthält</h2>
    <div class="subContainer1">
      <div style="float:left; width:30%">
        <img
          style="max-width: 100%;"
          src="../images/lillydoo-little-blowballs-design-preview-tp.jpg"
        />
      </div>

      <div style="float: right;width:70%">
        <h4>10 Lillydoo Windeln</h4>
        <ul style="display: inline">
          <li>
            0 % Parfüme & Lotionen, 100 % LILLYDOO Schutz
          </li>

          <li>
            Extra weich und super bequem
          </li>

          <li>
            Mit unseren Turbo Tunneln für eine ideale Passform und schnelle
            Absorption
          </li>
        </ul>
      </div>
    </div>

    <div class="subContainer2">
      <div style="float:left; width:37%; margin-right: 20px;">
        <img
          style="max-width: 100%;"
          src="../images/water-wipes-15-small.jpg"
        />
      </div>

      <div style="float: right; width:60%">
        <h4>
          15 Feuchttücher mit 99 % Wasser
        </h4>

        <ul style="display: inline">
          <li>
            0 % Parfüme & PEGs, 100 % biologisch abbaubar
          </li>

          <li>
            Natürlich rein, extra mild, Alternative zu "Wasser & Watte"
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SecondContainer"
};
</script>

<style scoped lang="scss">
.secondContainer {
  height: auto;
  background-color: #f8f8f8;
  margin-top: 20px;
  flex-direction: row;
}
.topText {
  font-family: cera_proregular, Helvetica, Roboto, Arial, sans-serif;
  text-transform: none;
  font-size: 1.688rem;
  line-height: 1.2;
  text-transform: none;
  margin-bottom: 10px;
  font-weight: normal;
  text-align: center !important;
}

.subContainer1 {
  width: 50%;
  float: left;
  height: auto;
}

.subContainer2 {
  width: 50%;
  float: right;
  height: auto;
}
</style>
