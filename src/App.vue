<template>
  <div id="app">
    <Title/>
  </div>
</template>

<script>
import Title from '@/components/Title.vue';

export default {
  name: 'App',
  components: {
    Title
  }
}
</script>

<style lang="scss">
#app {
  display:flex;
  justify-content:center;
  align-items:center;
  height: 100vh;
  
}
</style>
