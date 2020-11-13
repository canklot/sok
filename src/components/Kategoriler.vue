<template>
  <div class="Kategoriler">
    <div class="Baslik">Süt & süt ürünleri</div>
    <button class="Kategori">Süt</button>
    <button class="Kategori">Yoğurt</button>
    <button class="Kategori">Ayran & kefir</button>
    <button class="Kategori">Beyaz Peynir</button>
    <button class="Kategori">Krem Peynir</button>
    <button class="Kategori">Yöresel Gurme Peynir</button>
    <button class="Kategori">Kaymak & Krema</button>
    <button class="Kategori">Tereyağ & Margarin</button>
    <button class="Kategori">Maya</button>
    <button class="Kategori">Kaşar Peyniri</button>
    <button class="Kategori">Kaşar Peyniri</button>
    <button class="Kategori">Kaşar Peyniri</button>
  </div>
</template>

/* -------------Scripts--------------- */
<script>
export default {};
</script>

/* -------------Styles--------------- */
<style>
@import url('https://fonts.googleapis.com/css2?family=Work+Sans:wght@698&display=swap');


.Baslik{
    font-size: 15px;
    padding: 10px;
    font-family: 'Work Sans', sans-serif;
}
.Kategori {
  float: left;
  padding: 10px;
  margin: 0px;
  line-height: 3px;
  
}
.Kategori:hover {
  border: 2px solid rgba(5,81,159,.5);
  
  border-radius: 15px;
}
</style>
