<template>
  <div id="app">
    <HeaderComp/>  
    <MainComp/>
    <FooterComp/>
  </div>
</template>

<script>

import "bootstrap"
import HeaderComp from './components/HeaderComp.vue'
import MainComp from './components/MainComp.vue'
import FooterComp from './components/FooterComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp,
    FooterComp
  }
}
</script>

<style lang="scss">

@import "bootstrap/dist/css/bootstrap.min.css";
@import "./components/style/variabili.scss";
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300&family=Montserrat:wght@100;200;300;500&family=Mulish&family=Nunito:wght@200&family=Poppins:wght@200&family=Prompt&family=Ubuntu:wght@300&family=Varela+Round&display=swap');

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  color: white;
}

</style>
