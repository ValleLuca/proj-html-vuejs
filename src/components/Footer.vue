<template>
  <div>
  <footer-top />
  <footer-center />
  </div>
</template>

<script>
import FooterCenter from './section/sectionFooter/FooterCenter.vue'
import FooterTop from './section/sectionFooter/FooterTop.vue'
export default {
  name: 'Footer',
  components: { 
    FooterTop, 
    FooterCenter 
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">



</style>
