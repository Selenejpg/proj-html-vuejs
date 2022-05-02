<template>
  <div class="bg d-flex align-items-center justify-content-evenly margin">
    <div class="margin-left">
      <h3>Achieve your fitness goals</h3>
      <p>Flexible membership packages to suit all levels of athlete and achieve your fitness goals</p>
    </div>

    <div class="margin-right">
      <div class="d-flex mt-3 justify-content-center">
        <button type="button" class="btn btn-primary">JOIN US TODAY</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  //Cambiare il nome con quello del componente creato
  name: 'OttavaSezione',
}
</script>

<style scoped lang="scss">
@import "../style/variabili.scss";

.bg{
  background-image: url(../../assets/img/home-parallax.jpg);
  height: 140px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}


  button{
    background-color: transparent;
    border-color: white;
    color: white;
    padding: 15px;
  }

  button:hover {
    background-color: transparent;
    border-color: white;
  }

  .margin-left{
    margin-left: 10%;
  }

  .margin-right{
    margin-right: 12%;
  }

  p{
    font-size: 12px;
  }

  .btn{
    margin-top: -25px;
  }
</style>