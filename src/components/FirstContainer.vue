<template>
  <div class="firstContainer container-fluid">
    <h2 class="topText">
      Wie es funktioniert
    </h2>
    <div class="row">
      <div class="col-md-4">
        <img
          src="../images/lillydoo-your-trialbox-icon.svg"
          class="mx-auto d-block"
        />
        <h4>DEIN TESTPAKET</h4>
        <p>
          Wir schenken Dir die Produkte,
          <br />
          Du übernimmst nur das Porto.
        </p>
      </div>
      <div class="col-md-4">
        <img
          src="../images/lillydoo-your-flexibility-icon.svg"
          class="mx-auto d-block"
        />

        <h4>DEINE FLEXIBILITÄT</h4>
        <p>
          Erste Monatsbox nach 14 Tagen für 49,50 € <br />
          erhalten. Oder noch vor der ersten Lieferung <br />kündigen.
        </p>

        <p>
          <a
            class="hrefP"
            href="https://www.lillydoo.com/de/windel-abo"
            target="blank"
          >
            Erfahre hier mehr über das
            <br />
            LILLYDOO Windel-Abo.
          </a>
        </p>
      </div>

      <div class="col-md-4">
        <img
          src="../images/lillydoo-your-subscription-icon.svg"
          class="mx-auto d-block"
        />

        <h4>DEINE MONATSBOX</h4>
        <p>
          Jederzeit Windelgröße, Designs und Lieferintervalle<br />
          anpassen oder weitere Produkte hinzufügen.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FirstContainer"
};
</script>

<style scoped lang="scss">
.firstContainer {
  /* flex-direction: row;
  height: auto; */
  background-color: #f8f8f8;
  padding: 15px;
  /* margin-top: 20px; */
}
.topText {
  font-family: cera_proregular, Helvetica, Roboto, Arial, sans-serif;
  text-transform: none;
  font-size: 1.688rem;
  line-height: 1.2;
  text-transform: none;
  padding-top: 15px;
  margin-bottom: 10px;
  font-weight: normal;
  text-align: center !important;
}

/* .iconsInfo {
  list-style: none;
  display: flex;
  justify-content: space-evenly;
} */
.hrefP {
  text-decoration: none;
  color: #00afab;
}

h4,
p {
  text-align: center;
}
</style>
