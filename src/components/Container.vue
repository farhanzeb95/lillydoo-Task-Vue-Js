<template>
  <div class="container">
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from './HelloWorld.vue';
export default {
    name: 'Container',
    components:{
        HelloWorld
    }
}
</script>

<style scoped lang="scss">
.container {
    display: flex;
    min-height: 35.25rem;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    background-image: url('/img/header-trialbox-desktop.8d7d7516.jpg');
    margin-top: 20px;
}
</style>