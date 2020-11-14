<template>
  <div class="Adres">
    <img class="ucgen" src="../images/ucgen.png" />
    <div class="SilikAdres">Adress Seçin</div>
    <button class="MaviAdres">
      <p>Adres Seç</p>
      <p class="ok">&#8250;</p>
    </button>
    <div class="griArkaplan">
      <img class="bisiklet" src="../images/bisiklet.png" />
      <div class="adreseTeslim">Adrese Teslim</div>
      <div class="minSepet">Min sepet</div>
      <div class="gonderim">Gönderim</div>
      <img class="market" src="../images/market.png" />
      <div class="gelAl">Marketten Gel Al</div>
      <div class="minSepet">Min sepet</div>
    </div>
  </div>
</template>

/* -------------Scripts--------------- */
<script>
export default {};
</script>

/* -------------Styles--------------- */
<style>
@import url("https://fonts.googleapis.com/css2?family=Work+Sans:wght@698&display=swap");

* {
  float: left;
}
.ucgen {
  height: 30px;
  margin: 10px;
  padding-left: 300px;
}
.SilikAdres {
  padding: 15px;
  text-align: center;
  color: rgba(51, 41, 10, 0.5);
}
.MaviAdres {
  color: #05519f;
  text-align: center;
  padding: 15px;
  padding-left: 180px;
}
.ok {
  margin-left: 5px;
  padding-top: 5px;
  font-size: 30px;
  font-weight: 900;
  line-height: 5px;
  height: 25px;
  width: 25px;
  border-radius: 50%;
  border-style: solid;
  border-width: 1px;
  border-color: blue;
  display: inline-block;
  text-align: center;
}
.bisiklet {
  margin-top: 10px;
}
.adreseTeslim {
  padding: 15px;
}
.minSepet {
  padding: 15px;
  color: rgba(51, 41, 10, 0.5);
}
.gonderim {
  padding: 15px;
  color: rgba(51, 41, 10, 0.5);
}
.market {
  padding-top: 15px;
  margin-left: 180px;
}
.gelAl {
  padding-top: 15px;
  padding-left: 5px;
  font-weight: 700;
}
.griArkaplan {
  background-color: #f6f6f6;
  width: 1100px;
}
</style>
