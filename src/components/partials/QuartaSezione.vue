<template>
  <div class="bg-color">
    <div>
      <div class="text-center pt-5 pb-4">
        <h1 class="fs">REAL WORLD RESULTS</h1>
        <img src="../../assets/img/divider-xx-red.png" alt="">
      </div>
      
      <div class="d-flex mb-3 margin flex-left align-items-center">
        
        <div class="bg-cards me-3 padding d-flex">
          <img class="reviews" src="../../assets/img/review_1-compressor.jpg" alt="">
          <div class="p-2">
            <p>"The trainers at Ayada Gym have helped me reach my fitness goals beyond anything I could have hoped for. I love it!"</p>
            <span>-Tara Smith</span>
          </div>
        </div>

        <div class="bg-cards paddingsimon padding d-flex">
          <img class="reviews" src="../../assets/img/review_3-compressor-2.jpg" alt="">
          <div>
            <p>"The atmosphere at Ayada Gym is amazing, the people are even better. All in all, it is a great place to work out."</p>
            <span>-Simon Chel</span>
          </div>
        </div>
      </div>

      <div class="d-flex margin flex-left align-items-center">
        
        <div class="bg-cards me-3 padding d-flex">
          <img class="reviews" src="../../assets/img/review_2-compressor.jpg" alt="">
          <div class="p-2">
            <p>"The facilities at Ayada Gym stood out to me the most. They are well maintained and have high quality equipment."</p>
            <span class="d-flex flex-wrap">-Jen Wirth</span>
          </div>
        </div>

        <div class="bg-cards paddingjeff padding d-flex">
          <img class="reviews" src="../../assets/img/review_4-compressor-2.jpg" alt="">
          <div>
            <p class="">No bad things to say about Ayada Gym, they are top notch at every corner and truly take care of their customers.</p>
            <span class="">-Jeff Glum</span> 
          </div>
        </div>
      </div>
    </div>

    <div>
      <div class="paddingimg">
        <div class="text-center mt-5 pb-4">
          <h1 class="fs">HIGH PERFORMANCE FACILITIES</h1>
          <img src="../../assets/img/divider-xx-red.png" alt="">
        </div>
        
        <div class="d-flex me-2 flex-wrap justify-content-center">
          <div class="me-4 mb-4">
            <img src="../../assets/img/home-image1.jpg" alt="">
          </div>
          <div class="me-4 mb-4">
            <img src="../../assets/img/home-image2.jpg" alt="">
          </div>
          <div class=" mb-4">
            <img src="../../assets/img/home-image3.jpg" alt="">
          </div>
          <div class="me-4">
            <img src="../../assets/img/home-image4.jpg" alt="">
          </div>
          <div class="me-4">
            <img src="../../assets/img/home-image54.jpg" alt="">
          </div>
          <div class="">
            <img src="../../assets/img/home-image6.jpg" alt="">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  //Cambiare il nome con quello del componente creato
  name: 'QuartaSezione',
}
</script>

<style scoped lang="scss">
@import "../style/variabili.scss";

.bg-color {
  background-color: $shark;
}

.bg-cards{
  background-color: $darkershark;
}

p{
  font-size: 10px;
  color: gray;
  margin-top: 15px;
  margin-left: 10px;
}

span{
  color: gray;
  font-size: 10px;
  margin-left: 10px;
}

.reviews{
  width: 100px;
  height: 100px;
  margin-top: 10px;
}

.padding{
  padding: 20px;
}

.margin{
  margin-left: 20%;
  margin-right: 21%;
}

.paddingsimon{
  padding: 24px;
}

.paddingjeff{
  padding-top: 19px;
  padding-left: 19px;
}

.fs{
  font-size: 25px;
}

.paddingimg{
  padding-top: 80px;
  padding-bottom: 130px;
}


</style>