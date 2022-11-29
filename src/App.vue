<template>
  <div>
    <TheHeader />
    <TheMain />
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue';
import TheMain from './components/TheMain.vue';
export default {
  name: 'App',

  components: {
    TheHeader,
    TheMain,
  }
}
</script>

<style>
#app{
    margin: 0;
    padding: 0;
    font-family:sans-serif;
    box-sizing: border-box;
}
</style>
