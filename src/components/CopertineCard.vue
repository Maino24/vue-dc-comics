<template>
    <div class="card">
        <img :src="dettaglioCard.thumb" alt="">
       <!-- <h5>{{ dettaglioCard.price }}</h5>-->
        <h6>{{ dettaglioCard.series }}</h6>
        <!--<span>{{ dettaglioCard.type }}</span>-->
    </div>
</template>

<script>
    export default {
        name: `CopertineCard`,
        props: {
            dettaglioCard: Object
        }
    }
</script>

<style lang="scss" scoped>

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

.card{
    
    width: calc(100% / 6);
    padding: 0;
    margin: 0;
    img{
        height: 150px;
        
    }

    h6{
        color: white;
        text-align: center;
    }
}

</style>