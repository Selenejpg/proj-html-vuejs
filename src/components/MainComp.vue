<template>
  <main>
    <PrimaSezione/>
    <SecondaSezione/>
    <TerzaSezione/>
    <QuartaSezione/>
    <QuintaSezione/>
    <SestaSezione/>
    <SettimaSezione/>
    <OttavaSezione/>
  </main>
</template>

<script>

import PrimaSezione from './partials/PrimaSezione.vue'
import SecondaSezione from './partials/SecondaSezione.vue'
import TerzaSezione from './partials/TerzaSezione.vue'
import QuartaSezione from './partials/QuartaSezione.vue'
import QuintaSezione from './partials/QuintaSezione.vue'
import SestaSezione from './partials/SestaSezione.vue'
import SettimaSezione from './partials/SettimaSezione.vue'
import OttavaSezione from './partials/OttavaSezione.vue'


export default {
  //Cambiare il nome con quello del componente creato
  name: 'MainComp',
  components: {
    PrimaSezione,
    SecondaSezione,
    TerzaSezione,
    QuartaSezione,
    QuintaSezione,
    SestaSezione,
    SettimaSezione,
    OttavaSezione
  }
}
</script>

<style scoped lang="scss">
 /*Inserire style componente*/
</style>