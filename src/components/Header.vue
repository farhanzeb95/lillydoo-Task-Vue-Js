<template>
  <div class="header container-fluid">
    <OverlayDiv class="offset-md-7 col-md-4" />
  </div>
</template>

<script>
import OverlayDiv from "./OverlayDiv";
export default {
  name: "Header",
  components: {
    OverlayDiv
  }
};
</script>

<style scoped lang="scss">
.header {
  display: flex;
  min-height: 35.25rem;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  background-image: url("../images/header-trialbox-desktop.jpg");
}
</style>
