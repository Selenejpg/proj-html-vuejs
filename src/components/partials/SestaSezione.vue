<template>
  <div class="bg pt-5">
    <div class="text-center">
      <h1>MEET OUR TRAINERS</h1>
      <img class="mt-4 pt-2" src="../../assets/img/divider-xx-red.png" alt="">
    </div>
    

    <!-- PARTE DA DINAMICIZZARE -->
    <div class=" d-flex mt-5 flex-wrap justify-content-center flex-row">
      <div v-for="(element, index) in cards"
          :key="index"
          class="d-flex me-4  cards flex-column">

        <img class="width" :src="element.img" alt="">
        <div class="padding">
          <h2>{{element.name}}</h2>
          <span>{{element.trainer}}</span>
          <p>{{element.lorem}}</p>
          <div class="d-flex pt-2">
            <div class="square"><i class="fa-brands fa-facebook-f"></i></div>
            <div class="square"><i class="fa-brands fa-twitter"></i></div>
            <div class="square"><i class="fa-brands fa-instagram"></i></div>
          </div>
        </div>  
      </div>
    </div>
   

    <div class="d-flex marginbutton justify-content-center">
      <button type="button" class="btn btn-primary">VIEW ALL TRAINERS</button>
    </div>

  </div>
</template>

<script>
export default {
  //Cambiare il nome con quello del componente creato
  name: 'SestaSezione',
  data() {
    return{
      cards: [
        {
          img: require('../../assets/img/trainer1.jpg'),
          name: "Ann Baker",
          trainer:"Personal Trainer",
          lorem: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores sint molestias fugit ipsa amet voluptatem. Eaque ratione"
        },
        {
          img: require('../../assets/img/trainer3.jpg'),
          name: "Anne Warren",
          trainer:"Personal Trainer",
          lorem: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores sint molestias fugit ipsa amet voluptatem. Eaque ratione"
        }, 
        {
          img: require('../../assets/img/trainer4.jpg'),
          name: "Peter Rice",
          trainer:"Personal Trainer",
          lorem: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores sint molestias fugit ipsa amet voluptatem. Eaque ratione"
        },
      ]
    }
  }
}
</script>

<style scoped lang="scss">
@import "../style/variabili.scss";

.fa-brands{
  width: 70px;
  color: white;
  background-color: $darkershark;
  width: 35px;
  height: 35px;
  padding: 10px;
  margin-top: 5px;
  margin-right: 10px;
  text-align: center; 
}

.bg{
  background-color: $darkershark;
  padding-bottom: 70px;
}

p{
  font-size: 10px;
  padding-top: 10px;
}

span{
  font-size: 12px;
  font-weight: 500;
}

h2{
  font-size: 16px;
}

.cards{
  background-color: $shark;
  width: 20%;
  height: 430px;

}

.padding{
  padding: 30px;
}

button{
  background-color: transparent;
  border-color: gray;
  color: gray;
  padding: 15px;
}

button:hover {
  background-color: transparent;
  border-color: $chestnutrose;
}

.marginbutton{
  margin-top: 60px;
}
</style>