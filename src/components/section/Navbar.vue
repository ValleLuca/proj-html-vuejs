<template>
  <div>
      <nav>
          <ul class="d-flex justify-content-between align-items-center p-4 design">
              <li>
                <a href="#">
                  <i class="fas fa-home"></i>
                </a>
              </li>
              <li class="d-flex flex-column align-items-center">
                <a href="#">
                  <i class="fab fa-pagelines"></i>
                </a>
                <span>TRATMENTS</span>
                <span>Face & Body</span>
              </li>
              <li class="d-flex flex-column align-items-center">
                <a href="#">
                  <i class="fas fa-male"></i>
                </a>
                <span>TRATMENTS</span>
                <span>Face & Body</span>
              </li>
              <li class="d-flex flex-column align-items-center">
                <span>Avada SPA</span>
              </li>
              <li class="d-flex flex-column align-items-center">
                <a href="#">
                  <i class="fas fa-heart"></i>
                </a>
                <span>TRATMENTS</span>
                <span>Face & Body</span>
              </li>
              <li class="d-flex flex-column align-items-center">
                <a href="#">
                  <i class="fas fa-bookmark"></i>
                </a>
                <span>TRATMENTS</span>
                <span>Face & Body</span>
              </li>
              <li class="d-flex flex-column align-items-center">
                <a href="#">
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
}

</style>