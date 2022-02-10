<template>
    <div class="container optionContainer">
      <div class="row justify-content-center text-center">
        <div class="row">
          <div class="col">
            <h2 class="textFontSize">Luxury Spa Experience</h2>
          </div>
        </div>
        <div class="row my-3 optionBox">
          <i class="fab fa-envira fa-flip-horizontal fa-2xl"></i>
        </div>
        <div class="row d-flex justify-content-center">
          <div class="col-8 optionBox fs-5">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti esse voluptate autem recusandae eos error repudiandae.
          </div>
        </div>
        <div class="row d-flex justify-content-center">
          <div class="col-1 border-top my-4"> </div>
        </div>
        <div class="row d-flex justify-content-center">
          <div class="col-8">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi, delectus! Laudantium architecto reprehenderit quis ut nemo at, labore perspiciatis cupiditate provident. Impedit non fugit architecto, ut doloribus dolorem voluptates doloremque debitis, inventore deleniti ratione quis harum mollitia laboriosam voluptas? Atque!
          </div>
        </div>
        <div class="optionButtonDescr">
          <button class="rounded-pill p-2 px-5 mt-4">OUR APPROACH</button>
        </div>
      </div>
    </div>
</template>

<script>

export default {
    name: 'MainSectionDescription',
}
</script>

<style scoped lang="scss">

.optionButtonDescr{
  button{
    background-color: white;
    color: #c5b39d;
    border: 1px solid #c5b39d;
    &:hover{
      color: #5aadbd;
      border: 1px solid #5aadbd;
    }
  }
}

.optionContainer{
  margin-top: 100px;
}

.textFontSize{
  font-size: 50px;
}

.optionBox{
  color: #b6ad9f;
}

</style>