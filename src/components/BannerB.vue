<template>
  <div>
    <div class="alan-2">
      <v-btn class="buton2" depressed>
        Kurumsal
      </v-btn>
      <v-btn class="buton2" depressed>
        Yatırımcı İlişkileri
      </v-btn>
    </div>
    <div class="alan-1">
      <img class="logo" src="../images/soklogo.svg" />
      <div class="buton1">
        <img class="ekmeklogo" src="../images/ekmeklogo.png" />
        <p class="metin1">Kategoriler</p>
        <p class="metin2">˅</p>
      </div>
      <div class="fix"></div>
      <div class="acilirmenu">
        <div class="menuitem"><p class="menuitemmetin">Kategoriler</p></div>
        <div class="menuitem"><p class="menuitemmetin">Kategoriler</p></div>
        <div class="menuitem"><p class="menuitemmetin">Kategoriler</p></div>
        <div class="menuitem"><p class="menuitemmetin">Kategoriler</p></div>
        <div class="menuitem"><p class="menuitemmetin">Kategoriler</p></div>
        <div class="menuitem"><p class="menuitemmetin">Kategoriler</p></div>
      </div>
      <div class="search">
        <i class="fas fa-search fa-2x"></i>
        <input class="searchtype" v-model="search" placeholder="Ör.Yumurta" />
      </div>
      <div class="sagtaraf">
        <i class="fas fa-gift fa-2x"></i>
        <img class="hediye" src="../images/hediye.png" />
        <p class="iconmtn">Kampanyalar</p>
        <i class="fas fa-user fa-2x"></i>
        <img class="adam" src="../images/adam.png" />
        <p class="iconmtn2">Giriş Yap</p>
        <p class="iconmtn1">Üye Ol</p>
        <i class="fas fa-shopping-cart fa-2x"></i>
        <img class="sepet" src="../images/sepet.png" />
        <div class="fiyat"><p>₺0,00</p></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.fiyat {
  float: left;
  width: 50px;
  padding-left: 5px;
  margin-left: 20px;
  margin-top: 5px;
  border-radius: 4px;
  background-color: red;
  color: white;
}
.sagtaraf i {
  float: left;
  margin-left: 20px;
}
.iconmtn {
  float: left;
  margin-top: 10px;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: 500;
  font-size: 15px;
  color: black;
  margin-left: 10px;
}
.iconmtn2 {
  float: left;

  font-family: Arial, Helvetica, sans-serif;
  font-weight: 500;
  font-size: 15px;
  color: black;
  margin-left: 10px;
}

.iconmtn1 {
  margin-top: 10px;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: 500;
  font-size: 15px;
  color: black;
  margin-left: 30px;
  float: left;
  margin-top: 15px;
  margin-left: -55px;
}
.sagtaraf {
  margin-left: 20px;
  float: left;
  margin-top: 40px;
}

.alan-1 {
  height: 115px;
  background-color: #ffe000;
}
.logo {
  height: 49px;
  width: 54px;
  margin-left: 80px;
  margin-top: 30px;
  float: left;
}
.buton1 {
  width: 230px;
  height: 53px;
  background-color: blue;
  float: left;
  margin-left: 80px;
  margin-top: 30px;
  cursor: pointer;
  border-radius: 5px;
}

.buton1:hover ~ .acilirmenu {
  visibility: visible !important;
}

.acilirmenu:hover {
  visibility: visible !important;
}

.ekmeklogo {
  float: left;
  margin-left: 30px;
  margin-top: 5px;
}
.metin1 {
  float: left;
  margin-top: 20px;
  margin-left: 10px;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: 500;
  font-size: 15px;
  color: white;
}

.metin2 {
  float: left;
  margin-top: 20px;
  margin-left: 50px;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: 500;
  font-size: 15px;
  color: white;
}

.acilirmenu {
  width: 230px;
  height: 400px;
  margin-top: 93px;
  visibility: hidden;
  border-radius: 5px;
  float: left;
  margin-left: -230px;
}

.menuitem {
  border-bottom-style: solid;
  border-bottom-color: grey;
  border-bottom-width: 1px;
  width: 230px;
  height: 50px;
  border-radius: 5px;
  background-color: white;
}

.menuitem :hover {
  background-color: rgb(196, 194, 194);
}

.menuitemmetin {
  height: 50px;
  padding-top: 20px;
  padding-left: 30px;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: 500;
  font-size: 15px;
  color: black;
  cursor: pointer;
}

.fix {
  height: 30px;
  width: 230px;

  float: left;
  margin-left: -230px;
  margin-top: 73px;
}
.fix:hover ~ .acilirmenu {
  visibility: visible;
}
.search {
  width: 553px;
  height: 52px;
  background-color: white;
  float: left;
  margin-top: 30px;
  margin-left: 30px;
  border-radius: 4px;
}
.search i {
  height: 50px !important;
  width: 50px !important;
  color: black !important;
  margin-top: 10px;
  margin-left: 20px;
  float: left;
}
.searchtype {
  height: 52px;
  width: 450px;
  float: left;
}
.hediye {
  float: left;
}
.adam {
  padding-left: 10px;
  float: left;
}
.sepet {
  padding-left: 10px;
  float: left;
}
.buton2 {
  float: left;
  margin-left: 10px;
  margin-top: 10px;
  padding: .1rem !important;
  padding-top: .1rem !important;
  font-family: icomoon !important;
  font-size: 10px  !important;
  color: white !important;
  background-color:blue !important;
  height: 20px !important;
}
.alan-2{
  float: right;
  margin-right: 500px;
  height: .1rem !important;
  background-color:#ffe000;
}
/* .alan-2 ~ .button {
  background-color:blue;
} */
</style>
