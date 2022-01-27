<template>
  <div id="app">
    <header-container/>
    <jumbotron-box/>
    <navbar-container/>
  </div>
</template>

<script>
import HeaderContainer from './components/HeaderContainer.vue'
import JumbotronBox from './components/JumbotronBox.vue'
import NavbarContainer from './components/NavbarContainer.vue'

export default {
  name: 'App',
  components: {
    HeaderContainer,
    JumbotronBox,
    NavbarContainer,
  }
}
</script>

<style lang="scss">
@import './style/main.scss'
</style>
