<script>
export default {
    data(){

        return{
            // product:{
            //         "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
            //         "price": "$19.99",
            //         "series": "Action Comics",
            //         "type": "comic book",
            // }

        };

    },
    props:{
        product:Object
    }


}





</script>


<template>

<div class="unico-prodotto">

<div class="tutte-img">
    <img :src="product.thumb" :alt="product.series">
</div>

<h1>
    {{ product.series }}
</h1>

<h2>
    {{ product.type }}
</h2>

<h3>
    {{ product.price}}
</h3>


</div>



</template>



<style lang="scss" scoped>

.unico-prodotto{
        width: 25%;
        padding: 40px;
        border: 1px solid white;
        text-align: center;

            .tutte-img{
                width: 100%;
                  img {
                    width: 100%;
                    max-width: 100%;
                    height: auto; 
                  }
            }

}


</style>