<template>
  <div class="bg">
    <div class="poligono d-flex justify-content-center">
      <img src="../../assets/img/Polygon 2.png" alt="">
    </div>
    <div>
      <div class="text-center margin-top">
        <h2>PERFORMANCE NEWS</h2>
        <img class="mt-4 mb" src="../../assets/img/divider-xx-red.png" alt="">
      </div>

      <div class="d-flex flex-wrap justify-content-center">
        <div class="card-custom-first-third">
          <img class="img-cards" src="../../assets/img/blog1.jpg" alt="">
          <div class="p-4">
            <h3>Train with free weights or your body weight?</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores sint molestias fugit ipsa amet voluptatem. Eaque ratione[...]</p>
          </div>
        </div>
        <div class="card-custom">
          <img class="img-cards" src="../../assets/img/blog6.jpg" alt="">
          <div class="p-4">
            <h3>Nutritional advice that will keep you training</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores sint molestias fugit ipsa amet voluptatem. Eaque ratione[...]</p>
          </div>
        </div>
        <div class="card-custom-first-third">
          <img class="img-cards" src="../../assets/img/trainer4.jpg" alt="">
          <div class="p-4">
            <h3>Simple principles for your next workout</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores sint molestias fugit ipsa amet voluptatem. Eaque ratione[...]</p>
          </div>
        </div>
      </div>

      <div class="d-flex flex-wrap justify-content-center mt-4">
        <div class="card-custom-first-third marginegativo">
          <img class="img-cards" src="../../assets/img/blog4.jpg" alt="">
          <div class="p-4">
            <h3>To be number one, train like you're number two</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores sint molestias fugit ipsa amet voluptatem. Eaque ratione[...]</p>
          </div>
        </div>
        <div class="card-custom">
          <img class="img-cards" src="../../assets/img/trainer3.jpg" alt="">
          <div class="p-4">
            <h3>Top 5 mistakes every gym member makes</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores sint molestias fugit ipsa amet voluptatem. Eaque ratione[...]</p>
          </div> 
        </div>
        <div class="card-custom-first-third marginegativo">
          <img class="img-cards" src="../../assets/img/trainer1.jpg" alt="">
          <div class="p-4">
            <h3>The myths of shedding body fat explored</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores sint molestias fugit ipsa amet voluptatem. Eaque ratione[...]</p> 
          </div>
        </div>
      </div>
    </div>

    <div class="d-flex marginbutton justify-content-center">
      <button type="button" class="btn btn-primary">READ ALL ARTICLES</button>
    </div>
    
  </div>
</template>

<script>
export default {
  //Cambiare il nome con quello del componente creato
  name: 'SettimaSezione',
}
</script>

<style scoped lang="scss">
@import "../style/variabili.scss";

.poligono{
  margin-top: -4px;
}

.bg{
  background-color: $shark;
  padding-bottom: 80px;
}

.img-cards{
  width: 100%;
}

.card-custom{
  background-color: $darkershark;
  width: 18%;
  margin-right: 20px;
}

h3{
  font-size: 16px;
}

p{
  font-size: 12px;
  color: gray;
  margin-top: 15px;
}

.margin-top{
  margin-top: 80px;
}

.mb{
  margin-bottom: 50px;
}

.card-custom-first-third{
  background-color: $darkershark;
  width: 18%;
  margin-right: 20px;
  height: 380px;
}

.marginegativo{
  margin-top: -70px;
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