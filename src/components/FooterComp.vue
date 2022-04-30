<template>
  <footer>
    <FooterDinamico/>
    <FooterStatico/>
  </footer>
</template>

<script>

import FooterDinamico from './partials/FooterDinamico.vue'
import FooterStatico from './partials/FooterStatico.vue'

export default {
  //Cambiare il nome con quello del componente creato
  name: 'FooterComp',
  components: {
    FooterDinamico,
    FooterStatico
  }
}
</script>

<style scoped lang="scss">
 /*Inserire style componente*/
</style>