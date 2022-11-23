<template>
    <div>
        <div class="containerMainTop">
            <h3> Content goes here </h3>
        </div>
        <div class="containerMainBottom">
            <nav>
                <ul>
                    <li><img class="img" src="../assets/img/buy-comics-digital-comics.png" alt=""> <span>DIGITAL COMICS</span> </li>
                    <li><img class="img" src="../assets/img/buy-comics-merchandise.png" alt=""><span>DC MERCHANDISE</span></li>
                    <li><img class="img" src="../assets/img/buy-comics-subscriptions.png" alt=""><span>SUBSCRIPTION</span></li>
                    <li><img class="img1" src="../assets/img/buy-comics-shop-locator.png" alt=""><span>COMIC SHOP LOCATOR</span></li>
                    <li><img class="img1" src="../assets/img/buy-dc-power-visa.svg" alt=""><span>DC POWER VISA</span></li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<script>
    export default {
  name: 'MainComp'
}

</script>

<style lang="scss" scoped>


*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
.containerMainTop{
    width: 100%;
    height: 150px;
    
    background-color: rgba(28, 28, 28, 1);
    
}

h3{
    color: white;
}

.containerMainBottom{
    width: 100%;
    height: 150px;
    display: flex;
    background-color: rgba(2, 130, 249, 1);
    justify-content: center;
    align-items: center;
}


ul{
    width: 80%;
    margin: auto;
    display: flex;
    list-style-type: none;
    justify-content: center;
    align-items: center;
    justify-content: space-around;
}

li{
    display: flex;
    justify-content: center;
    align-items: center;
}

.img{
    width: 20%;
    margin-right: 10px;
}

.img1{
    width: 15%;
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