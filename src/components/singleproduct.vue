<script>
export default{
      data(){

        return{
            product:{
                
            }

        };
      }
}
</script>

<template>
    <div class="unico-prodotto" v-for="(image,i) in images" :key="i">

        <div class="tutte-img">
            <img src="https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg" alt="19,97">
        </div>

        {{ image.series }}

    </div>
</template>

<style lang="scss"scoped>
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