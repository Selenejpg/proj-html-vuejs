<template>
  <div class="d-flex bg-image justify-content-center m-auto text-center">
    <div class="">
      <div class="circle d-flex justify-content-center align-items-center">
        <i class="fa-solid fa-link-slash"></i>
      </div>
      <h2>Strength & Conditioning</h2>
      <img class="divider" src="../../assets/img/divider-x-red.png" alt="">
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veniam, pariatur?</p>
    </div>
    <div>
      <div class="circle d-flex justify-content-center align-items-center">
        <i class="fa-solid fa-motorcycle"></i>
      </div>
      <h2>Fitness & Cardio</h2>
      <img class="divider" src="../../assets/img/divider-x-red.png" alt="">
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veniam, pariatur?</p>
    </div>
    <div>
      <div class="circle d-flex justify-content-center align-items-center">
        <i class="fa-brands fa-skyatlas"></i>
      </div>
      <h2>Flexibility & Rest</h2>
      <img class="divider" src="../../assets/img/divider-x-red.png" alt="">
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veniam, pariatur?</p>
    </div>
    <div>
      <div class="circle d-flex justify-content-center align-items-center">
        <i class="fa-solid fa-heart-pulse"></i>
      </div>
      <h2>Health & Diet</h2>
      <img class="divider" src="../../assets/img/divider-x-red.png" alt="">
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veniam, pariatur?</p>
    </div>
  </div>
</template>

<script>
export default {
  //Cambiare il nome con quello del componente creato
  name: 'TerzaSezione',
}
</script>

<style scoped lang="scss">
@import "../style/variabili.scss";

.m-auto{
  padding-left: 25%;
  padding-right: 25%;
  font-size: 10px;
  padding-top: 8%;
  padding-bottom: 10%;
}

.fa-solid{
  color: $chestrosevibrant;
  font-size: 20px;
}

.fa-brands{
  color: $chestrosevibrant;
  font-size: 20px;
}

.circle {
	border-radius: 50%;
	height: 50px;
	width: 50px;
	border: 2px solid $chestrosevibrant;
  margin-left: 35%;
	}	

.bg-image{
  background-image: url(../../assets/img/gym_bkgd_bw-compressor.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}

h2{
  font-size: 14px;
  margin-top: 20px;
  margin-bottom: 20px;
}

.divider {
  margin-bottom: 20px;
}

p{
  color: gray;
}
</style>