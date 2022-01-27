<template>
  <div id="app">
    
      <header-container/>

  </div>
</template>

<script>
import HeaderContainer from './components/HeaderContainer.vue'

export default {
  name: 'App',
  components: {
    HeaderContainer,
    
  }
}
</script>

<style lang="scss">
  @import '@/styles/main.scss'
</style>
