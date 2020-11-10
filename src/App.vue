/* -----------------------------------template-------------------- */
<template>
  <div id="app">
    <!-- <UrunDetay msg="BenimParametrem"/> -->
    <KampanyalarB msg="BenimParametrem"/>
    <PromosyonKoduB msg="BenimParametrem"/>
    <GirisYapB msg="BenimParametrem"/>
  </div>
</template>

/* -----------------------------------Script-------------------- */

<script>

//import UrunDetay from './components/UrunDetay.vue'
//import KampanyalarB from './components/KampanyalarB.vue'
//import PromosyonKoduB from './components/PromosyonKoduB.vue'
import GirisYapB from './components/GirisYapB.vue'


export default {
  name: 'App',
  components: {
    //UrunDetay
    //KampanyalarB
    //PromosyonKoduB
    GirisYapB
  }
}
</script>


/* -----------------------------------Style-------------------- */

<style>
#app {
  
}
</style>
