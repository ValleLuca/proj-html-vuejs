<template>
  <div id="app">
    <Header />
    <Main />
    <Footer />
    <go-top></go-top>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'
import GoTop from '@inotom/vue-go-top';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
    GoTop
  }
}
</script>

<style lang="scss">
@import "./assets/style/global.scss";



</style>
