<template>
  <div>
    <div class="cBackgroundNav">
      <div class="container">
        <div class="row">
          <div class="col">
            <Navbar />
          </div>
        </div>
      </div>
    </div>
    <div class="hBackground position-relative">
      <div class="position-absolute top-50 start-50 translate-middle text-light text-center">
        <p class="fs-1 textStyle">Give yourself permission</p>
        <div class="larghText">
          <h1 class="fontOption">Relax, Revive & Rejuvenate</h1>
        </div>
        <button class="rounded-pill p-2 px-5 text-light mt-4">EXPLORE TREATMNETS</button>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from './section/Navbar.vue'


export default {
  name: 'Header',
  components: {
    Navbar
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.cBackgroundNav{
  background-color: #fafafa;
}

.hBackground{
  background-image: url('../assets/img/avada-spa-slider-image-1-new.jpg');
  min-height: 1000px;
  button{
    background-color: #bcafa1;
    border: 1px solid #bcafa1;
    &:hover{
      background-color: #33a7b9;
      border: 1px solid #33a7b9;
    }
  }
}

.fontOption{
  font-size: 100px;
  font-family: 'Tinos', serif;
}

.larghText{
  width: 1500px;
}

.textStyle{
  font-family: 'IM Fell Double Pica', serif;
}

</style>
