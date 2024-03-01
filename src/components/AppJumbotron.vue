<script>

export default{
    name:"AppJumbotron",

    data(){
        return{

        }
    }
}

</script>

<template>

    <div class="jumbotron">
        <img src="https://immagini.insella.it/sites/default/files/news_gallery/2021/05/ducati_hypermotard_950_sp_38_uc287662_high.jpg" alt="jumbotron">
        <div class="jumbo-text">
            MOTO MOLTO TANTO BELLA
        </div>
        <button class="jumbo-btn">Compra</button>
    </div>
 
</template>

<style>

    .jumbotron{
        position:relative;
        max-width: 800px;
        margin: 0 auto;
    }

    img{
        width: 100%;
        border-radius: 20px;;
    }

    .jumbo-text{
        position:absolute;
        top:30px;
        left:50%;
        transform: translate(-50%);

        padding:15px;

        border-radius: 15px;

        background-color: rgba(0, 0, 0, .7);

        font-size:24px;
        font-weight: bold;;
    }

    .jumbo-btn{
        position:absolute;
        bottom:20px;
        left:50%;
        transform: translate(-50%);

    }

</style>
