<template>
  <div class="grid"> <!--implementare grid-->
      <div class="g-col-1" v-for="(elemnt, index) in box" :key="index"> 
          <img class="img-fluid" :src="elemnt.img" >
          <p>{{ elemnt.title }}</p>
          <p>{{ elemnt.text }}</p>
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



</style>