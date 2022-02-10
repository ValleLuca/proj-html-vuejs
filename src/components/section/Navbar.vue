<template>
  <div>
      <nav>
          <ul class="d-flex justify-content-between align-items-center p-4">
              <li>
                <a class="colorHome" href="#">
                  <i class="fas fa-home"></i>
                </a>
              </li>
              <li class="d-flex flex-column align-items-center colorText">
                <a class="colorTratment" href="#">
                  <i class="fab fa-pagelines"></i>
                </a>
                <span>TRATMENTS</span>
                <div>Face & Body</div>
              </li>
              <li class="d-flex flex-column align-items-center colorText">
                <a class="colorTratment" href="#">
                  <i class="fas fa-male"></i>
                </a>
                <span>ABOUT</span>
                <div>Our Team</div>
              </li>
              <li class="d-flex flex-column align-items-center">
                <img src="../../assets/img/avada-spa-logo-new.png">
              </li>
              <li class="d-flex flex-column align-items-center colorText">
                <a class="colorTratment" href="#">
                  <i class="fas fa-heart"></i>
                </a>
                <span>JOURNAL</span>
                <div>Tips & Tricks</div>
              </li>
              <li class="d-flex flex-column align-items-center colorText">
                <a class="colorTratment" href="#">
                  <i class="fas fa-bookmark"></i>
                </a>
                <span>BOOK nOW</span>
                <div>Special Offert</div>
              </li>
              <li class="d-flex flex-column align-items-center">
                <a class="colorHome" href="#">
                  <i class="fas fa-plus"></i>
                </a>
              </li>
          </ul>
      </nav>
  </div>
  <!--effettuare un ciclo for-->
</template>

<script>

export default {
  name: 'Navbar',
}
</script>

<style scoped lang="scss">

ul{
  list-style-type: none;
  margin-bottom: 0;
}

li{
  cursor: pointer;
  div{
    font-size: 12px;
  }
};

.colorHome{
  color: #34a5b7;
}

.colorTratment{
  color: #b7ad9f;
}

.colorText{
  color: #72757e;
}

</style>