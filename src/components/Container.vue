<template>
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <img
          class="img-fluid"
          :src="
            require('@/images/lillydoo-testpaket-' + dynamicImage + '0.jpg')
          "
        />
        <div class="floater">
          <img class="img-fluid" src="../images/oekotex_green_de.svg" />
        </div>
      </div>

      <SizeSelector
        class="col-md-6"
        :selected-image="dynamicImage"
        @change="updateImage"
      />
    </div>
  </div>
</template>

<script>
import SizeSelector from "./SizeSelector";
export default {
  name: "Container",
  components: { SizeSelector },
  data() {
    return {
      dynamicImage: "1"
    };
  },
  methods: {
    updateImage(image) {
      this.dynamicImage = image;
    }
  }
};
</script>

<style scoped lang="scss">
.container {
  display: flex;
  min-height: 35.25rem;
  // border: 2px solid red;
  margin-top: 20px;
  padding: 20px;
  flex-direction: row;
}

.subContainer1 {
  display: flex;
  min-height: 35.25rem;
  // border: 2px solid green;
  width: 50%;
  float: left;
}

.subContainer2 {
  display: flex;
  min-height: 35.25rem;
  // border: 2px solid black;
  width: 50%;
  float: right;
}

.planText {
  font-family: cera_proregular, Helvetica, Roboto, Arial, sans-serif;
  font-size: 1.688rem;
  font-weight: inherit;
}

.selectContainer {
  margin-bottom: 30px;
}

.floater {
  position: absolute;
  width: 24%;
  top: 13%;
  left: 9%;
  z-index: 10;
  box-shadow: -2px 2px 6px -3px rgba(0, 0, 0, 0.4);
  border-radius: 3px;
}
.row{
   padding:20px;
}
</style>
