<template>
    <div>
        <div class="jumbo">
            
        </div>
        <div class="containerMainTop">
            <div class="container-cards">
                <button class="btnSeries"><h3>CURRENT SERIES</h3></button>
                <div class="card">
                    <CopertineCard
                        v-for="(elem, index) in card"
                        :key="index"
                        :dettaglioCard="elem"/>
                </div>
                <button class="btnMore">LOAD MORE</button>
            </div>
            
        </div>
        <div class="containerMainBottom">
            <nav>
                <ul>
                    <li><img class="img" src="../assets/img/buy-comics-digital-comics.png" alt=""> <span>DIGITAL COMICS</span> </li>
                    <li><img class="img" src="../assets/img/buy-comics-merchandise.png" alt=""><span>DC MERCHANDISE</span></li>
                    <li><img class="img" src="../assets/img/buy-comics-subscriptions.png" alt=""><span>SUBSCRIPTION</span></li>
                    <li><img class="img1" src="../assets/img/buy-comics-shop-locator.png" alt=""><span>COMIC SHOP LOCATOR</span></li>
                    <li><img class="img2" src="../assets/img/buy-dc-power-visa.svg" alt=""><span>DC POWER VISA</span></li>
                </ul>
            </nav>
        </div>

        
    </div>

    

</template>

<script>

import CopertineCard from './CopertineCard.vue'

    export default {
  name: 'MainComp',
  components: {
    CopertineCard
  },
  data() {
    return {
        card: [
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
    "price": "$19.99",
    "series": "Action Comics",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
    "price": "$3.99",
    "series": "American Vampire 1976",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
    "price": "$16.99",
    "series": "Aquaman",
    "type": "graphic novel"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
    "price": "$2.99",
    "series": "Batgirl",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
    "price": "$3.99",
    "series": "Batman",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
    "price": "$2.99",
    "series": "Batman Beyond",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
    "price": "$3.99",
    "series": "Batman/Superman",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
    "price": "$4.99",
    "series": "Batman/Superman Annual",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
    "price": "$5.99",
    "series": "Batman: The Joker War Zone",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
    "price": "$6.99",
    "series": "Batman: Three Jokers",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
    "price": "$4.99",
    "series": "Batman: White Knight Presents: Harley Quinn",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
    "price": "$16.99",
    "series": "Catwoman",
    "type": "graphic novel"
  }
]
    }
  }
}

</script>

<style lang="scss" scoped>


*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

.jumbo{
    background-image: url(../assets/img/jumbotron.jpg);
    background-size: cover;
    height: 300px;
}

.btnSeries{
    background-color: rgba(2, 130, 249, 1);
    color: white;
    padding: 10px 35px;
    position: relative;
    bottom: 20px;
    left: 10px;
    border: 0;
}

.containerMainTop{
    width: 100%;
    background-color: rgba(28, 28, 28, 1);
    padding-bottom: 20px;
}

.container-cards{
    width: 70%;
    margin: auto;
}

.card {
    display: flex;
    flex-wrap: wrap;
    padding: 20px 10px; 
    justify-content: space-around;
}

h3{
    color: white;
}

.btnMore{
    background-color: rgba(2, 130, 249, 1);
    color: white;
    padding: 10px 35px;
    display: flex;
    margin: auto;
    border: 0;
}

.containerMainBottom{
    width: 100%;
    display: flex;
    background-color: rgba(2, 130, 249, 1);
    justify-content: center;
    align-items: center;
    padding: 40px 0;
}

ul{
    width: 70%;
    margin: auto;
    display: flex;
    list-style-type: none;
    justify-content: center;
    align-items: center;
    justify-content: space-between;
}

li{
    display: flex;
    justify-content: center;
    align-items: center;
    width: calc(100% / 5);
}

.img{
    width: 20%;
    margin-right: 10px;
}

.img1{
    width: 15%;
    margin-right: 10px;
}

.img2{
    width: 20%;
    margin-right: 10px;
}

span{
    justify-content: center;
    align-items: center;
    vertical-align: middle;
    color: white;
    font-size: 0.8rem;
}

 

</style>

