<template>
  <div class="header">
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from './HelloWorld.vue';
export default {
    name: 'Header',
    components:{
        HelloWorld
    }
}
</script>

<style scoped lang="scss">
.header {
    display: flex;
    min-height: 35.25rem;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    background-image: url('../images/header-trialbox-desktop.jpg');
}
</style>
