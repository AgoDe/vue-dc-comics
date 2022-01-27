<template>
  <div id="app">
    
      <header-container/>

      <main-container/>

      <footer-container/>

  </div>
</template>

<script>
import HeaderContainer from './components/HeaderContainer.vue';
import MainContainer from './components/MainContainer.vue';
import FooterContainer from './components/FooterContainer.vue'


export default {
  name: 'App',
  components: {
    HeaderContainer,
    MainContainer,
    FooterContainer,

  }
}
</script>

<style lang="scss">
  @import '@/styles/main.scss'
</style>
