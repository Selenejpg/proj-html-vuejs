<template>
  <div class="bg-gray">
    <div class="margin">
      <div class="d-flex justify-content-center">
        <h2 class="mb-4">WORLD CLASS Fitness</h2>
      </div>

      <div class="d-flex justify-content-center">
        <div class="mb-4">
          <img src="../../assets/img/divider-xx-red.png" alt="">
        </div>  
      </div>
      <div class="d-flex justify-content-center">
        <p>At Ayada Gym, everything we do from top to bottom is of the highest quality to ensure we're equipped to help you reach your goals of a healthy and fit lifestyle</p>
      </div>
    </div>   
  </div>
</template>

<script>
export default {
  //Cambiare il nome con quello del componente creato
  name: 'PrimaSezione',
}
</script>

<style scoped lang="scss">
  .bg-gray{
    background-color: #25292c;
    padding: 70px;
  }

  p{
    color: gray;
    text-align: center;
  }

  .margin{
    padding-left: 20%;
    padding-right: 20%;
    padding-top: 30px;
    padding-bottom: 30px;
  }
</style>