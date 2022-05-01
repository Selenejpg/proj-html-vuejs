<template>
  <div>
    <div class="bg-hero text-center d-flex justfy-content-center align-item-center align-items-center">
      <div class="margin">
        <p class="mb-4">"I fear not the man who has practiced 10.000 kicks once, but i fear the man who has practiced one kick 10.000 times"</p>
        <span>BRUCE LEE · QUOTE OF THE DAY </span>
      </div>
      
    </div>
  </div>
  
</template>

<script>
export default {
  //Cambiare il nome con quello del componente creato
  name: 'QuintaSezione',
}
</script>

<style scoped lang="scss">
@import "../style/variabili.scss";

.bg-hero{
  background-image: url(../../assets/img/home-testimonial-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  height: 430px;
}

.margin{
  margin-left: 30%;
  margin-right: 30%;
  font-size: 20px;
  font-weight: 700;
}

</style>