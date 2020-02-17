<template>
  <div class="header">
    <OverlayDiv />
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
