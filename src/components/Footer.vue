<template>
  <div>
  <footer-top />
  <footer-center />
  <footer-bottom />
  </div>
</template>

<script>
import FooterBottom from './section/sectionFooter/FooterBottom.vue'
import FooterCenter from './section/sectionFooter/FooterCenter.vue'
import FooterTop from './section/sectionFooter/FooterTop.vue'

export default {
  name: 'Footer',
  components: { 
    FooterTop, 
    FooterCenter,
    FooterBottom 
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">



</style>
