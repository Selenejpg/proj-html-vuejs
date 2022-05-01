<template>
<div class="bg-color">
  <div class="d-flex justify-content-center">
      <img class="margin-polygon" src="../../assets/img/Polygon 1.png" alt="">
  </div>
  <div class="d-flex padding justify-content-evenly marginphoto">
    <div class="">
      <img src="../../assets/img/home_img-compressor-400x222.jpg" alt="">
    </div>
    <div class="margin-right">
      <h2 class="mb-4">Sign Up for a free training session!</h2>
      <span class="gray padding-input">Name*</span>
      <div class="input-group mb-4">
        <input type="text" class="form-control" placeholder="Username" aria-label="Username" aria-describedby="basic-addon1">
      </div>
      <span class="gray padding-input">Email</span>
      <div class="input-group mb-5">
        <span class="input-group-text" id="basic-addon1">@</span>
        <input type="text" class="form-control" placeholder="Username" aria-label="Username" aria-describedby="basic-addon1">
      </div>
      <button type="button" class="btn w-custom btn-danger">START NOW</button>
    </div>
  </div>
</div>

</template>

<script>
export default {
  //Cambiare il nome con quello del componente creato
  name: 'SecondaSezione',
}
</script>

<style scoped lang="scss">
@import "../style/variabili.scss";

  .margin-polygon{
    margin-top: -2px
  }

  .gray {
    color: gray;
  }

  .bg-color{
    background-color: #202123;
  }

  .marginphoto{
    margin-left: 240px;
  }

  .margin-right{
    margin-right: 160px;
  }

  .padding {
    padding-top: 90px;
    padding-bottom: 110px;
  }

  .w-custom {
    width: 100%;
    background-color: $chestnutrose;
    border-color: $chestnutrose;
  }

  .btn:hover{
    background-color: $chestrosevibrant;
    border-color: $chestrosevibrant;
  }
</style>