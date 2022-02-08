<template>
  <div>
    <main-section-description />
    <main-section-therapies />
    <main-section-price />
  </div>
</template>

<script>
import MainSectionDescription from './section/sectionMain/MainSectionDescription.vue'
import MainSectionPrice from './section/sectionMain/MainSectionPrice.vue'
import MainSectionTherapies from './section/sectionMain/MainSectionTherapies.vue'

export default {
  name: 'Main',
  components: { 
    MainSectionDescription,
    MainSectionTherapies,
    MainSectionPrice 
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">



</style>
