<template>
  <header>
    <!-- Header logo e menu -->
    <div class="p-4 d-flex justify-content-between align-items-center">
      <!-- logo -->
      <div>
        <img class="logo-ayada ms-5" src="../assets/img/gym_logo_1x.png" alt="">
      </div>

      <!-- menu da dinamicizzare -->
      <div>
        <ul class="d-flex">
          <li v-for="(element, index) in vociHeader"
              :key="'A' + index">
      
            <a href="">{{vociHeader[index]}}</a>
          </li>
        </ul>
      </div>
    </div>
    
    <!-- titolo -->
    <div class="d-flex m-top text-white justify-content-center align-items-center">
      <h1 class="title">NO PAIN NO GAIN</h1>
    </div>

    <!-- paragrafo sottostante e bottone -->
    <div class="d-flex mt-2 justify-content-center">
      <p>Motivation is what gets you started. Habit is what keeps you going.</p>
    </div>
    <div class="d-flex mt-3 justify-content-center">
      <button type="button" class="btn btn-primary">JOIN US TODAY</button>
    </div>
  </header>
</template>

<script>
export default {
  //Cambiare il nome con quello del componente creato
  name: 'HeaderComp',
  data(){
    return{
      vociHeader: ["HOME", "ABOUT US","FACILITIES","MEMBERSHIP","TESTIMONIALS","BLOG"]
    }
  }
  
}
</script>

<style scoped lang="scss">
@import "./style/variabili.scss";

  header{
    background-image: url(../assets/img/home-banner.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 650px;
  }

  .logo-ayada{
    width: 150px;
  }

  ul{
    list-style-type: none;
  }

  a{
    text-decoration: none;
    color: white;
    margin-right: 35px;
    font-size: 12px;
  }

  a:hover{
    color: $chestnutrose;
  }

  .m-top{
    margin-top: 13%;
  }

  .title {
    font-weight: 700;
    font-size: 70px;
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
</style>