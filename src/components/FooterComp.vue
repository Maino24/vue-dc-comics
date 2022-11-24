<template>
    <div>
        <div class="sfondoFooter">
            <div class="container">
                <div class="containerList">
                    <div>
                        <ul>
                            <li><h4>DC COMICS</h4></li>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                        <ul>
                            <li><h4 class="h4Shop">SHOP</h4></li>
                            <li>Shop DC</li>
                            <li>Shop DC collectibles</li>
                        </ul>
                    </div>
                    <div>
                        <ul>
                            <li><h4>DC</h4></li>
                            <li>Terms Of Use</li>
                            <li>Privacy policy (New)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent Workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>Contact US</li>
                        </ul>
                    </div>
                    <div>
                        <ul>
                            <li><h4>SITES   </h4></li>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>Dc Kids</li>
                            <li>Dc UNiverse</li>
                            <li>Dc Power Visa</li>
                        </ul>
                    </div>
                </div>
                
                
                <div class="img-footer">
                    
                </div>
            </div>
        </div>
        <div class="sfondoBottom">
            <div class="containerSfondoBottom">
                <div>
                    <button>SIGN-UP NOW!</button>
                </div>
                <div class="containerSocial">
                    <div>
                        <h4>FOLLOW US</h4>
                    </div>
                    <div class="containerSocial2">
                        <img class="social" src="../assets/img/footer-facebook.png" alt="">
                        <img class="social" src="../assets/img/footer-twitter.png" alt="">
                        <img class="social" src="../assets/img/footer-youtube.png" alt="">
                        <img class="social" src="../assets/img/footer-pinterest.png" alt="">
                        <img class="social" src="../assets/img/footer-periscope.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>    
</template>

<script>
    export default {
        name: `FooterComp`
    }
</script>

<style lang="scss" scoped>

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

.sfondoFooter{
    width: 100%;
    //height: 350px;
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    //position: relative;
    //z-index: 1;
    
}

.container{
    width: 70%;
    margin: auto;
    display: flex;
    justify-content: space-between;
}

ul{
    padding-right: 20px;
    
}

h4{
    color: white;
}

.h4Shop{
    color: white;
    margin-top: 20px;
}

li{
    list-style-type: none;
    color: grey;
    //padding-top: 5px;
}

.containerList{
    display: flex;
    padding: 60px 0;
}

.img-footer{
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    width: 50%;
    
}

.sfondoBottom{
    background-color: rgba(48, 48, 48, 1);
    height: 100px;
}

.containerSfondoBottom{

    width: 70%;
    display: flex;
    margin: auto;
    justify-content: space-between;
    align-items: center;

}

button{
    border:  2px solid blue;
    padding: 10px;
    background-color: rgba(48, 48, 48, 1);
    color: white;
}



.containerSocial{
    
    display: flex;
    justify-content: space-around;
    align-items: center;

    h4{
        color: blue;
        font-size: 1rem;
    }

}

.containerSocial2{
    display: flex;
    margin: auto;
    justify-content: center;
    align-items: center;
}

.social{
    margin: auto;
    padding-left: 20px;
    margin-left: 0;
}



</style>