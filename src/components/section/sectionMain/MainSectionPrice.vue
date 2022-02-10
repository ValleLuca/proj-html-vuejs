<template>
    <div class="py-5 cBackground">
        <div class="container">
        <div class="row align-items-center">
            <div class="col-6">
                <div class="border shadow p-3 mb-5 bg-body imgContainer">
                    <img class="img-fluid p-3" src='../../../assets/img/face_and_body_treatments-new.jpg'>
                </div>
            </div>
            <div class="col optionCol">
                <div>
                    <h3 class="optionText">Face & Body Treatments</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil tenetur excepturi eligendi consectetur odio consequatur modi ratione fugiat. In, quaerat?</p>
                </div>
                <div>
                    <div class="boxPrice" @click="active = !active">
                        <div class="p-2" v-show="!active" >
                            <i class="fas fa-plus-square"></i>
                            <span class="ms-2 optionText">Oil Massage</span>
                        </div>
                        <div class="p-2" v-show="active">
                            <i class="fas fa-minus-square chColor"></i>
                            <span class="ms-2 optionText">Oil Massage</span>
                            <p class="pt-3">$62 For 2 Hours - Lorem ipsum dolor sit amet</p>
                        </div>
                    </div>

                    <div class="boxPrice mt-1" @click="mActive = !mActive">
                        <div class="p-2" v-show="!mActive" >
                            <i class="fas fa-plus-square"></i>
                            <span class="ms-2 optionText">Manicure</span>
                        </div>
                        <div class="p-2" v-show="mActive">
                            <i class="fas fa-minus-square chColor"></i>
                            <span class="ms-2 optionText">Manicure</span>
                            <p class="pt-3">$62 For 2 Hours - Lorem ipsum dolor sit amet</p>
                        </div>
                    </div>

                    <div class="boxPrice mt-1" @click="aromActive = !aromActive">
                        <div class="p-2" v-show="!aromActive" >
                            <i class="fas fa-plus-square"></i>
                            <span class="ms-2 optionText">Aromatherapy</span>
                        </div>
                        <div class="p-2" v-show="aromActive">
                            <i class="fas fa-minus-square chColor"></i>
                            <span class="ms-2 optionText">Aromatherapy</span>
                            <p class="pt-3">$62 For 2 Hours - Lorem ipsum dolor sit amet</p>
                        </div>
                    </div>
                </div>
                <div class="mt-5">
                    <button class="treatmentButton py-2 px-4 rounded-pill">BOOK AN APPOINTMENT</button>
                </div>
            </div>
        </div>
    </div>
    </div>
</template>

<script>

export default {
    name: 'MainSectionPrice',
    data() {
        return{
            active: false,
            mActive: false,
            aromActive: false
        }
    }
}
</script>

<style scoped lang="scss">

.cBackground{
    background-color: #f9f9f9;
}

.optionCol{
    padding: 5%;
    h3{
        font-size: 70px;
    }
}

.boxPrice{
    border: 2px solid #cbcbcb;
    &:hover{
        cursor: pointer;
    }
    div{
        background-color: white;
        span{
            color: #b8ad9f;
        }
    }
}

.chColor{
    color: #b8ad9f;
}

.treatmentButton{
    border: 2px solid #b8ad9f;
    background-color: #f9f9f9;
    color: #b8ad9f;
    &:hover{
        color: #5aadbd;
        border: 2px solid #5aadbd;
    }
}

.optionText{
  font-family: 'Tinos', serif;
}

</style>