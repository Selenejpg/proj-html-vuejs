<template>
  <div class="bg d-flex pt-5 padding justify-content-center align-items-center pt-2">
    <div class="d-flex left flex-column">
      <h4>COME FIND US</h4>
      <span class="lightgray">12345 North Main Street</span>
      <span class="lightgray">New York, NY 555555</span>
      <span class="lightgray">Phone: 1.800.555.6789</span>
      <span class="lightgray">Email: info@your-domain.com</span>
    </div>
    <div class="d-flex margin flex-column">
      <h4>RECENT POSTS</h4>
      <span class="lightgray">>Train with free weights or your <br> body weight?</span>
      <div class="divider mb-2"></div>
      <span class="lightgray">>Nutritional advice that will keep <br> you training</span>
      <div class="divider mb-2"></div>
    </div>
    <div class="d-flex flex-column">
      <h4>OPENING DAYS</h4>
      <span class="lightgray">Weekdays Monday - Friday</span>
      <span class="hours mb-2">09:00 - 19:00</span>
      <span class="lightgray">Weekdays Saturday - Sunday</span>
      <span class="hours mb-2">09:00 - 21:00</span>
    </div>
    <div class="ms-5 right">
      <img class="width" src="../../assets/img/gym_ad-compressor.jpg" alt="">
    </div>
  </div>
</template>

<script>
export default {
  //Cambiare il nome con quello del componente creato
  name: 'FooterDinamico',
}
</script>

<style scoped lang="scss">
@import "../style/variabili.scss";
 
 .width{
   width: 60%;
 }

 .bg{
   background-color: $darkershark;
 }

 .divider{
   border-top: 1px solid gray;
 }

 .margin{
   margin-left: 30px;
   margin-right: 30px;
 }

 h4{
   font-size: 10px;
   color: $dovegrey;
 }
 
.lightgray{
  color: $edward;
  font-size: 10px;
  margin-bottom: 8px;
}

.hours{
  color: $dovegrey;
  font-size: 8px;
}

.left{
  margin-left: 20%;
  
}

.right{
  margin-right: 12%;
}

.padding{
  padding-bottom: 50px;
}
</style>