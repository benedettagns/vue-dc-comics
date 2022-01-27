<template>
  <div id="app">
    <header-container/>
    <jumbotron-box/>
  </div>
</template>

<script>
import HeaderContainer from './components/HeaderContainer.vue'
import JumbotronBox from './components/JumbotronBox.vue'

export default {
  name: 'App',
  components: {
    HeaderContainer,
    JumbotronBox,
  }
}
</script>

<style lang="scss">
@import './style/main.scss'
</style>
