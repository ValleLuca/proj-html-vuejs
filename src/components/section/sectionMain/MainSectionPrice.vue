<template>
    <div class="container">
      <div class="row align-items-baseline">
          <div class="col-6">
              <div class="border shadow p-3 mb-5 bg-body imgContainer">
                <img class="img-fluid p-3" src='../../../assets/img/face_and_body_treatments-new.jpg'>
              </div>
          </div>
          <div class="col optionCol">
                <div>
                    <h3 class="">Face & Body Treatments</h3>
                    <p class="">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil tenetur excepturi eligendi consectetur odio consequatur modi ratione fugiat. In, quaerat?</p>
                </div>
                <div>
                    <div>
                        <div>
                            <i class="fas fa-plus-square"></i>
                            <span class="ms-2">Oil Massage</span>
                        </div>
                        <div>
                            <i class="fas fa-minus-square"></i>
                            <span class="ms-2">Oil Massage</span>
                        </div>
                    </div>
                </div>
          </div>
      </div>
    </div>
</template>

<script>

export default {
    name: 'MainSectionPrice',
}
</script>

<style scoped lang="scss">

.optionCol{
    padding: 5%;
    h3{
        font-size: 70px;
    }
}

</style>