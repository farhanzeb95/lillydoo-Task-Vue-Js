<template>
  <div class="secondContainer container-fluid">
    <h2 class="topText">Dein Testpaket enthält</h2>
    <div class="row">
      <div class="col-md-6 row">
        <div class="col-md-4">
          <img
            class="img-fluid"
            src="../images/lillydoo-little-blowballs-design-preview-tp.jpg"
          />
        </div>

        <div class="col-md-8">
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

      <div class="col-md-6 row">
        <div class="col-md-4">
          <img
            class="img-fluid"
            src="../images/water-wipes-15-small.jpg"
          />
        </div>

        <div class="col-md-8">
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
  </div>
</template>

<script>
export default {
  name: "SecondContainer"
};
</script>

<style scoped lang="scss">
.secondContainer {
  margin-top: 40px;
  margin-bottom: 40px;
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
</style>
