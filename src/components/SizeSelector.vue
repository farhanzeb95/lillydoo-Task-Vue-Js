<template>
  <div class="col-md-4 offset-sm-2">
    <h2>
      Entdecke unsere Hautfreundlichkeit
    </h2>
    <div class="plainText">
      <p>WÄHLE DEINE GRÖSSE</p>

      <ul class="buttonList">
        <li class="sizebutton" :class="isSelected(1)" @click="sendImage(1)">
          <span
            >1<br />
            (2-5 KG)
          </span>
        </li>
        <li class="sizebutton" :class="isSelected(2)" @click="sendImage(2)">
          <span
            >1<br />
            (2-5 KG)
          </span>
        </li>
        <li class="sizebutton" :class="isSelected(3)" @click="sendImage(3)">
          <span
            >1<br />
            (2-5 KG)
          </span>
        </li>
        <li class="sizebutton" :class="isSelected(4)" @click="sendImage(4)">
          <span
            >1<br />
            (2-5 KG)
          </span>
        </li>
        <li class="sizebutton" :class="isSelected(5)" @click="sendImage(5)">
          <span
            >1<br />
            (2-5 KG)
          </span>
        </li>
      </ul>
    </div>

    <div class="plainText">
      <p>
        Teste jetzt unsere hautfreundlichen Windeln und erhalte unsere
        Feuchttücher mit 99 % Wasser zu Größe 1 - 3 oder die Sensitiven
        Feuchttücher zu Größe 4 - 5. Wir zahlen die Produkte, Du nur den
        Versand.
      </p>
    </div>
    <div class="listContainer">
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
            style="color:#00afab"
            >Versandkosten
          </a>
        </li>
      </ul>
    </div>
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
      required: true
    }
  },
  methods: {
    sendImage(image) {
      this.$emit("change", image);
    },
    isSelected(number) {
      return number === this.selectedImage ? "btn-selected" : "";
    }
  }
};
</script>
<style lang="scss" scoped>
$button-color: #00afab;
.cartButton {
  margin-top: 14px;
  margin-bottom: 10px;

  font-size: 1.063rem;
  height: 45px;
  padding: 0 20px;
  min-width: 12rem;
  line-height: 2.8;
  background-color: $button-color;
  font-family: cera_proregular, Helvetica, Roboto, Arial, sans-serif;
  margin-top: 20px;
  width: 100%;
  border: none;
  color: #fff;

  &:hover {
    opacity: 0.5;
    cursor: pointer;
  }
}
.buttonList {
  list-style-type: none;
  display: flex;
  justify-content: space-between;

  li {
    margin-right: 5px;

    button.btn-selected,
    button:hover {
      background-color: #00afab;
      border-color: #00afab;
    }
  }
}

.listContainer {
  justify-content: space-between;
}

.plainText {
  margin-bottom: 30px;
}
.sizebutton {
  border: 1px solid #7c7c7c;
  text-align: center;
  padding: 7px 5px 2px 5px;
  color: #7c7c7c;
  margin-right: 10px;
  width: 20%;
  height: max-content;
  font-size: 1.1rem;

  &:hover {
    color: #fff;
    cursor: pointer;
    background-color: #00afab;
    border-color: #00afab;
  }
}

.sizebutton li.flex-active,
.sizebutton li.selected {
  background-color: #00afab;
  color: #fff;
}
</style>
