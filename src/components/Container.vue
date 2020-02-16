<template>
  <div class="container">
    <div class="subContainer1">
      <img style="float:right" src="../images/lillydoo-testpaket-10.jpg">
    </div>

    <div class="subContainer2">
      <form>
        <h2 class="planText">
          Entdecke unsere Hautfreundlichkeit
        </h2>
        <div class="selectContainer">
          <p>WÄHLE DEINE GRÖSSE</p>
        </div>

        <p>Teste jetzt unsere hautfreundlichen Windeln und erhalte unsere Feuchttücher mit 99 % Wasser zu Größe 1 - 3 oder
        die Sensitiven Feuchttücher zu Größe 4 - 5. Wir zahlen die Produkte, Du nur den Versand.
        </p>

        <ul>
        <li style="color:#00afab">
                      Automatischer Übergang ins jederzeit kündbare Windel-Abo für 49,50 € pro Lieferung.

        </li>
        <li>
          Preise inkl. MwSt., ggf. zzgl.
          <a href="https://www.lillydoo.com/de/zahlung-und-versand" target="_blank"/>
        </li>
        </ul>
        <button class="cartButton">
            In den Warenkorb legen
        </button>
      <!-- <ul>
        <li>
          <button>1</button>
        </li>
        <li>
            <button>1</button>
        </li>
        <li>
            <button>1</button>
        </li>
        <li>
            <button>1</button>
        </li>
        <li>
            <button>1</button>
        </li>
      </ul> -->
          </form>
    </div>

  </div>
</template>

<script>

</script>

<style scoped lang="scss">
.container {
    display: flex;
    min-height: 35.25rem;
    border: 2px solid red;
    margin-top: 20px;
}

.subContainer1{
    display: flex;
    min-height: 35.25rem;
    border: 2px solid green;
    width: 50%;
    float: left;
}

.subContainer2{
    display: flex;
    min-height: 35.25rem;
    border: 2px solid black;
    width: 50%;
    float: right;
}

.planText{
    font-family: cera_proregular,Helvetica,Roboto,Arial,sans-serif;
    font-size: 1.688rem;
    font-weight: inherit
}

.selectContainer{
  margin-bottom: 30px;

}

.cartButton{
    margin-top: 14px;
    margin-bottom: 10px;
    font-size: 1.063rem;
    height: 45px;
    padding: 0 20px;
    min-width: 16rem;
    line-height: 2.8;
    background-color: #00afab;
    font-family: cera_proregular,Helvetica,Roboto,Arial,sans-serif;
    margin-top: 20px;
    width: 100%;
    border: none;
    cursor: pointer;
}

.cartButton:hover{
  opacity: 0.5;
}
</style>
