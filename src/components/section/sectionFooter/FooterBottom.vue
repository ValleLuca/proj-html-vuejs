<template>
  <div>
    <div class="bgImage position-relative">
      <div class="position-absolute top-50 start-50 translate-middle text-light text-center">
        <p>"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maiores ut natus aut, temporibus odio tenetur nostrum beatae. Quasi culpa tenetur porro esse vero? Quam cumque quos ducimus voluptatibus adipisci dolores, quidem ipsam dicta expedita voluptates sunt perferendis"</p>
        <p>FRIEDA FRIEDSON, MASSEUSE</p>
      </div>
    </div>
    <div class="backImg">
      <div class="container padding">
          <div class="row">
              <div class="col-2 d-flex justify-content-center align-items-center">
                <div class="optionBox text-center ">
                  <div class="p-3">
                    <div class="text-light fSizePerc fw-bold">25%</div>
                    <div class="text-light sizeFont">SPECIAL OFFERT</div>                    
                  </div>
                </div>
              </div>
              <div class="col d-flex align-items-center">
                <div>
                  <p class="text-light sizeCFooter">Take some time. Treat yourself. You deserve it.</p>
                  <p class="text-light">Book a treatment this month and receive a 25% on all further treatments</p>
                </div>
              </div>
              <div class="col-2 d-flex justify-content-center align-items-center">
                <div>
                  <button class="text-light px-4 py-2 rounded-pill optionButton">BOOK NOW</button>
                </div>
              </div>
          </div>
        </div>
    </div>
    <footer-botoom-end-page />
  </div>
</template>

<script>
import FooterBotoomEndPage from './footerBotoomSection/FooterBotoomEndPage.vue'

export default {
  name: 'FooterBottom',
  components: { 
    FooterBotoomEndPage 
  },

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">


.bgImage{
  background-image: url("../../../assets/img/Home-quota-new.jpg");
  background-position: left center;
  min-height: 700px;
  width: auto;
}

.backImg{
  background-image: url('../../../assets/img/ptb_cta-new.jpg');
}

.padding{
  padding: 150px 0;
}

.fSizePerc{
  font-size: 50px;
}

.sizeFont{
  font-size: 11px;
}

.sizeCFooter{
  font-size: 35px;
  font-family: 'Tinos', serif;

}

.optionButton{
  background-color: #b8ad9f;
  border: 1px solid #b8ad9f;
}

.optionBox{
  border: 1px solid #b8ad9f;
}
</style>