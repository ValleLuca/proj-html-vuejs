<template>
  <div class="grid"> <!--implementare grid-->
      <div class="border" v-for="(elemnt, index) in box" :key="index">
        <img class="img-fluid" :src="elemnt.img" >
        <div class="p-3">
            <p class="cText">{{ elemnt.title }}</p>
            <p class="bordoPers">{{ elemnt.text }}</p>
        </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'FooterCenter',
    data() {
        return {
            box: [
                {
                    img: require('../../../assets/img/Layer-1-new.jpg'),
                    title: "Hydrotherapy",
                    text: "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ducimus velit quos voluptatem repellat temporibus non officia molestiae alias maiores! Voluptatibus!"
                },
                {
                    img: require('../../../assets/img/Layer-2-new.jpg'),
                    title: "Massage",
                    text: "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ducimus velit quos voluptatem repellat temporibus non officia molestiae alias maiores! Voluptatibus!"
                },
                {
                    img: require('../../../assets/img/Layer-3-new.jpg'),
                    title: "Aromatherapy",
                    text: "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ducimus velit quos voluptatem repellat temporibus non officia molestiae alias maiores! Voluptatibus!"
                },
                {
                    img: require('../../../assets/img/Layer-4-new.jpg'),
                    title: "Heat Therapy",
                    text: "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ducimus velit quos voluptatem repellat temporibus non officia molestiae alias maiores! Voluptatibus!"
                },
                {
                    img: require('../../../assets/img/Layer-5-new.jpg'),
                    title: "Skin Care",
                    text: "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ducimus velit quos voluptatem repellat temporibus non officia molestiae alias maiores! Voluptatibus!"
                },
                {
                    img: require('../../../assets/img/Layer-6-new.jpg'),
                    title: "Spa Days",
                    text: "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ducimus velit quos voluptatem repellat temporibus non officia molestiae alias maiores! Voluptatibus!"
                },
                {
                    img: require('../../../assets/img/Layer-7-new.jpg'),
                    title: "Beauty Tretments",
                    text: "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ducimus velit quos voluptatem repellat temporibus non officia molestiae alias maiores! Voluptatibus!"
                },
                {
                    img: require('../../../assets/img/layer8-new.jpg'),
                    title: "Residential",
                    text: "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ducimus velit quos voluptatem repellat temporibus non officia molestiae alias maiores! Voluptatibus!"
                },
            ],
        }    
    }
}
</script>

<style scoped lang="scss">

.grid{
    display: grid;
    grid-template-columns: 25% 25% 25% auto;
}

.bordoPers{
    border-top: 1px dotted #c3af96;
}

.cText{
    color: #c3af96;
    font-family: 'Tinos', serif;
}

</style>