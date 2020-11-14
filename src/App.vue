/* -----------------------------------template-------------------- */
<template>
  <div id="app">
   <!--  <UrunDetay msg="BenimParametrem"/> -->
    <!-- <KampanyalarB msg="BenimParametrem"/> -->
    <!-- <PromosyonKoduB msg="BenimParametrem"/> -->
    <!-- <GirisYapB msg="BenimParametrem"/> -->
    <!-- <BannerB msg="BenimParametrem"/> -->
    <!-- <AktuelUrunler msg="BenimParametrem"/> -->
    <!-- <Kategoriler msg="BenimParametrem"/> -->
    <Adres msg="BenimParametrem"/>
  </div>
</template>

/* -----------------------------------Script-------------------- */

<script>

//import UrunDetay from './components/UrunDetay.vue'
//import KampanyalarB from './components/KampanyalarB.vue'
//import PromosyonKoduB from './components/PromosyonKoduB.vue'
//import GirisYapB from './components/GirisYapB.vue'
//import BannerB from './components/BannerB.vue'
//import AktuelUrunler from './components/AktuelUrunler.vue'
//import Kategoriler from './components/Kategoriler.vue'
import Adres from './components/Adres.vue'



export default {
  name: 'App',
  components: {
    //UrunDetay
    //KampanyalarB
    //PromosyonKoduB
    //GirisYapB
    //BannerB
    //AktuelUrunler
    //Kategoriler
    Adres
  }
}
</script>


/* -----------------------------------Style-------------------- */

<style>

#app {
  
}
</style>
