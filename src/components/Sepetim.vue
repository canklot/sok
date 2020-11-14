<template>
  <div class="Sepetim">
    <div class="baslik">Sepetim</div>
    <div class="alisveriseDevam">&#65308; Alışverişe Devam Et</div>
    
    <div class="beyazKutu">
      <img class="araba" src="../images/araba.png" />
      <div class="urunYok">Henüz sepetinizde ürün yok</div>
    </div>

    <div class="sagdakiKutu">
      <div class="kdv">KDV Dahil Toplam Tutar</div>
      <div class="tutar">₺0,00</div>
      <div class="promosyon">Promosyon Kodum Var</div>
    </div>
  </div>
</template>

/* -------------Scripts--------------- */
<script>
export default {};
</script>

/* -------------Styles--------------- */
<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins&display=swap");

* {
  font-family: poppins;
}
.baslik{
    font-weight:700;
    padding-left: 300px;
    padding-top: 100px;
    float: left;
}
.Sepetim{
   background-color:#f6f6f6;
   width: 100%;
   height: 900px;
}
.alisveriseDevam{
    float: left;
    padding-left: 720px;
    padding-top: 100px;
    color: rgba(51,41,10,.5);
    font-weight:800 ;
}
.beyazKutu{
    height: 300px;
    width: 970px;
    background-color: #fff;
    position: relative;
    top:150px;
    left:300px;
}
.araba{
    position: relative;
    left: 50%;
    height: 45px;
}
.urunYok{
    position: relative;
    left: 43%;
    height: 45px;
}
.sagdakiKutu{
    background-color: white;
    height: 100px;
    width: 240px;
    position: relative;
    left: 1330px;
    top:-150px;
    border-radius: 5px;
    padding:20px;
}
.kdv{
    font-size: 13px;
    font-weight: 600;
    width: 110px;
}
.tutar{
    background-color: #ffe000;
    position: relative;
    left:120px;
    top:-40px;
    width: 90px;
    border-radius: 5px;
    text-align: center;
    color: red;
    font-weight: bold;
}
.promosyon{
    position: relative;
    top:-20px;
    text-decoration: underline;
    font-size: 13px;
}
</style>
