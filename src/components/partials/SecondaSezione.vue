<template>
<div class="bg-color">
  <div class="d-flex justify-content-center">
      <img class="margin-polygon" src="../../assets/img/Polygon 1.png" alt="">
  </div>
  <div class="d-flex justify-content-center">
    <div class="">
      <img src="../../assets/img/home_img-compressor-400x222.jpg" alt="">
    </div>
    <div class="margin-left">
      <h2 class="">Sign Up for a free training session!</h2>
      <span class="gray">Name*</span>
      <div class="input-group mb-3">
        <input type="text" class="form-control" placeholder="Username" aria-label="Username" aria-describedby="basic-addon1">
      </div>
      <span class="gray">Email</span>
      <div class="input-group mb-3">
        <span class="input-group-text" id="basic-addon1">@</span>
        <input type="text" class="form-control" placeholder="Username" aria-label="Username" aria-describedby="basic-addon1">
      </div>
      <button type="button" class="btn btn-danger">Danger</button>
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
  .margin-polygon{
    margin-top: -2px
  }

  .gray {
    color: gray;
  }

  .bg-color{
    background-color: #202123;
  }
</style>