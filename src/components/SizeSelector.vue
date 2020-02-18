<template>
  <div>
          <h2 class="planText">
            Entdecke unsere Hautfreundlichkeit
          </h2>
          <div class="selectContainer">
            <p>WÄHLE DEINE GRÖSSE</p>
          </div>

        <ul class="buttonList">
          <li>
            <button :class="isSelected(1)" @click="sendImage(1)">1</button>
          </li>
          <li>
              <button :class="isSelected(2)" @click="sendImage(2)">2</button>
          </li>
          <li>
              <button :class="isSelected(3)" @click="sendImage(3)">3</button>
          </li>
          <li>
              <button :class="isSelected(4)" @click="sendImage(4)">4</button>
          </li>
          <li>
              <button :class="isSelected(5)" @click="sendImage(5)">5</button>
          </li>
        </ul>
          <p>
            Teste jetzt unsere hautfreundlichen Windeln und erhalte unsere
            Feuchttücher mit 99 % Wasser zu Größe 1 - 3 oder die Sensitiven
            Feuchttücher zu Größe 4 - 5. Wir zahlen die Produkte, Du nur den
            Versand.
          </p>

          <ul>
            <li style="color:#00afab">
              Automatischer Übergang ins jederzeit kündbare Windel-Abo für 49,50 €
              pro Lieferung.
            </li>
            <li>
              Preise inkl. MwSt., ggf. zzgl.
              <a
                href="https://www.lillydoo.com/de/zahlung-und-versand"
                target="_blank"
              >Versandkosten
              </a>
            </li>
          </ul>
          <button class="cartButton">
            In den Warenkorb legen
          </button>
  </div>
</template>
<script>
export default {
  name: "SizeSelector",
  props: {
    selectedImage: {
      type: Number,
      required: true,
    }
  },
  methods: {
    sendImage(image) {
      this.$emit('change', image)
    },
    isSelected (number) {
      return number === this.selectedImage ? 'btn-selected':''
    }
  }
}
</script>
<style lang="scss" scoped>
.cartButton {
  margin-top: 14px;
  margin-bottom: 10px;
  font-size: 1.063rem;
  height: 45px;
  padding: 0 20px;
  min-width: 16rem;
  line-height: 2.8;
  background-color: #00afab;
  font-family: cera_proregular, Helvetica, Roboto, Arial, sans-serif;
  margin-top: 20px;
  width: 100%;
  border: none;
  cursor: pointer;
  color: #fff;

  &:hover {
    opacity: 0.5;
  }
}
.buttonList {
  list-style-type: none;
  display: flex;

  li {
    float: left;
    margin-right: 5px;

    button.btn-selected, button:hover {
      color: #fff;
      background-color: #00afab;
    }
  }
}
</style>
