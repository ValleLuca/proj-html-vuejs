<template>
    <div class="container">
      <div class="row justify-content-center text-center">
        <div class="row">
          <div class="col">
            <h2>Luxury Spa Experience</h2>
          </div>
        </div>
        <div class="row">
          <i class="fab fa-envira fa-flip-horizontal"></i>
        </div>
        <div class="row d-flex justify-content-center">
          <div class="col-6">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium possimus aspernatur explicabo distinctio magni soluta ipsum nemo eveniet nihil, quis aperiam architecto. Eveniet omnis iure deserunt quam. Ipsam, unde dignissimos?
          </div>
        </div>
        <div class="row d-flex justify-content-center">
          <div class="col-1 border-top my-4"> </div>
        </div>
        <div class="row d-flex justify-content-center">
          <div class="col-6">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium possimus aspernatur explicabo distinctio magni soluta ipsum nemo eveniet nihil, quis aperiam architecto. Eveniet omnis iure deserunt quam. Ipsam, unde dignissimos?
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

</style>