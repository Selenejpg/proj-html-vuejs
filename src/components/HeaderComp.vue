<template>
  <header>
    <!-- Header logo e menu -->
    <div class="p-4 mt-2 d-flex justify-content-between align-items-center">
      <!-- logo -->
      <div>
        <img class="logo-ayada ms-5" src="../assets/img/gym_logo_1x.png" alt="">
      </div>

      <!-- menu da dinamicizzare -->
      <div>
        <ul class="d-flex">
          <li>
            <a href="">HOME</a>
          </li>
          <li>
            <a href="">ABOUT US</a>
          </li>
          <li>
            <a href="">FACILITIES</a>
          </li>
          <li>
            <a href="">MEMBERSHIP</a>
          </li>
          <li>
            <a href="">TESTIMONIALS</a>
          </li>
          <li>
            <a href="">BLOG</a>
          </li>
        </ul>
      </div>
    </div>
    
    <!-- titolo -->
    <div>
      <h1></h1>
    </div>

    <!-- paragrafo sottostante e bottone -->
    <div>
      <div>
        <p></p>
        <button></button>
      </div>
    </div>
    
  </header>
</template>

<script>
export default {
  //Cambiare il nome con quello del componente creato
  name: 'HeaderComp',
}
</script>

<style scoped lang="scss">
@import "./style/variabili.scss";

  header{
    height: 500px;
    background-image: url(../assets/img/home-banner.jpg);
    background-repeat: no-repeat;
    background-size: cover;
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
</style>