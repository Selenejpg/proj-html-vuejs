<template>
  <div class="d-flex padding bg justify-content-evenly align-items-center">
    <div>
      <p class="fs">&copy;Copyright 2012 - 2020 | Ayada Theme by Theme Fusion | All Rights Reserved | Powered by WordPress</p>
    </div>
    <div class="d-flex me">
      <div class="square"><i class="fa-brands fa-facebook-f"></i></div>
      <div class="square"><i class="fa-brands fa-twitter"></i></div>
      <div class="square"><i class="fa-brands fa-instagram"></i></div>
    </div>
  </div>
</template>

<script>
export default {
  //Cambiare il nome con quello del componente creato
  name: 'FooterStatico',
}
</script>

<style scoped lang="scss">
@import "../style/variabili.scss";

.fa-brands{
  width: 70px;
  color: white;
  background-color: $chestrosevibrant;
  width: 35px;
  height: 35px;
  padding: 10px;
  margin-right: 10px;
  text-align: center; 
}

.fs{
  font-size: 10px;
  margin-top: 20px;
  margin-left: 100px;
  color: $edward;
}

.me{
  margin-right: 120px;
}

.bg{
  background-color: rgb(29, 29, 29);
}

.padding{
  padding-top: 10px;
  padding-bottom: 10px;
}

</style>