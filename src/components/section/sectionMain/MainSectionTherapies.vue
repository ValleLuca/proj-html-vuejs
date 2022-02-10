<template>
    <div class="container mt-5">
      <div class="row text-center fontOption">
          <div class="col">
            <div class="optionTherapy fs-1">
                <i class="fa-solid fa-hands fa-flip-horizontal"></i>
                <p class="fs-5">Massages</p>
            </div>
          </div>
          <div class="col pt-4">
            <div class="optionTherapy fs-1">
                <i class="far fa-smile"></i>
                <p class="fs-5">Therapy</p>
            </div>
          </div>
          <div class="col">
            <div class="optionTherapy fs-1">
                <i class="fas fa-heart"></i>
                <p class="fs-5">Relazing</p>
            </div>
          </div>
          <div class="col pt-4">
            <div class="optionTherapy fs-1">
                <i class="far fa-moon"></i>
                <p class="fs-5">Meditation</p>
            </div>
          </div>
          <div class="col">
            <div class="optionTherapy fs-1">
                <i class="fas fa-snowflake"></i>
                <p class="fs-5">Natural Beauty</p>
            </div>
          </div>

      </div>
    </div>
</template>

<script>

export default {
    name: 'MainSectionTherapies',
}
</script>

<style scoped lang="scss">

.optionTherapy{
    color: #b8ad9f;
}

.fontOption{
  font-family: 'Tinos', serif;
}

</style>