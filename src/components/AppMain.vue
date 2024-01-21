<script>
import singleproduct from './singleproduct.vue';
export default {
    data() {
        return {
            images: [
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book",
                },
                {
                    "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560,c_limit/Aquaman-16.jpg",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel",
                },
                {
                    "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel",
                },
            ]
        };
    },
    components:{
        singleproduct
    }
    
}
</script>

<template>


            <main>



                <div class="bar-due">

                    <div>
                       <h1>COMICS</h1>
                    </div>

                    <div class="container-prodotti">
                       <singleproduct v-for="(image,i) in images" :key="i" />
                        <!-- v-for="(image,i) in images"/>
                        :key="i"
                        :product="image" -->

                        <!-- <div class="unico-prodotto" >

                            <div class="tutte-img">
                                <img :src="image.thumb" :alt="image.price">
                            </div>
                            
                            {{ image.series }}

                        </div> -->

                    </div>

                </div>

                <div class="bar-tre">

                    <ul>

                        

                        <li>
                        <img src="C:\Users\stefa\classe 114 boolean\vite-template\buy-comics-digital-comics.png" alt=""> 
                        <p>DIGITAL COMICS</p>
                        </li>

                        <li>
                        <img src="C:\Users\stefa\classe 114 boolean\vite-template\buy-comics-merchandise.png" alt=""> 
                        <p>DC MERCANDISE</p>
                        </li>

                        <li>
                        <img src="C:\Users\stefa\classe 114 boolean\vite-template\buy-comics-shop-locator.png" alt=""> 
                        <p>SUBSCRIPTION</p>
                        </li>

                        <li>
                        <img src="C:\Users\stefa\classe 114 boolean\vite-template\buy-comics-subscriptions.png" alt=""> 
                        <p>COMICS SHOP LOCATOR</p>
                        </li>
                    
                    

                        

                        
                    </ul>
                    

                </div>

                <div class="bar-quattro">

                    <div class="contenitore-lista-uno">
                        <ul>
                            <h2>dc comics</h2>

                            <li>
                                tv
                            </li>
                                
                            <li>
                                charachter
                            </li>

                            <li>
                                move
                            </li>

                            <li>
                                comics
                            </li>

                            <li>
                                video
                            </li>

                            <li>
                                News
                            </li>

                            <h3>
                                SHOP
                            </h3>

                            <li>
                                shop dc
                            </li>

                            <li>
                                shop dc
                            </li>


                        </ul>

                    </div>

                    <div class="contenitore-lista-due">

                        <ul>
                            <h2>DC</h2>

                            <li>
                                tv
                            </li>
                                
                            <li>
                            job
                            </li>

                            <li>
                                active
                            </li>

                            <li>
                                add chois
                            </li>

                            <li>
                                subscription
                            </li>

                            <li>
                                News
                            </li>

                        </ul>

                    </div>

                    <div class="contenitore-lista-tre">
                        <ul>
                            <h2>DC</h2>

                            <li>
                                tv
                            </li>
                                
                            <li>
                            job
                            </li>

                            <li>
                                active
                            </li>

                            <li>
                                add chois
                            </li>

                            

                        </ul>

                    </div>


                    <div class="logo-big">
                        <img src="C:\Users\stefa\classe 114 boolean\vite-template\dc-logo-bg.png"  alt="">
                    </div>

                    
                
                    
                </div>

            </main>
</template>

<style lang="scss" scoped>
.bar-due{
    border: 1px solid black;
    width: 100%;
    min-height: 150px;
    background-color: black;
    color: white;
        .container-prodotti{
            display: flex;
            flex-wrap: wrap;
                    // .unico-prodotto{
                    //     width: 25%;
                    //     padding: 40px;
                    //     border: 1px solid white;
                    //     text-align: center;

                    //     .tutte-img{
                    //         width: 100%;
                    //             img {
                    //                 width: 100%;
                    //                 max-width: 100%;
                    //                 height: auto; 
                    //             }

                    //     }

                    // }

        }

}




.bar-tre{
    border: 1px solid black;
    width: 100%;
    height: 150px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color:rgb(12, 124, 236);
    color: white;
       > ul{
          display: flex;
          justify-content: center;
            li{
                list-style: none;
                display: flex;
                text-align: center;

                  p{
                    margin-top: 20px;
                    margin-left: 30px;
                  }

            }
        
             img{
                width: 20%;
                
             }
       }
   
}





.bar-quattro{
    background-image: url('footer-bg.jpg');
    border: 1px solid black;
    width: 100%;
    height: 350px;
    display: flex;
    align-items: center;
    overflow: hidden;
    .contenitore-lista-uno{
        border: 1px solid black;
        margin-left: 100px;
           li{
            list-style: none;
            color:gray;
           }
           h2{
            color: white;
           }
           h3{
            color: white;
           }
    
    } 
    .contenitore-lista-due{
        border: 1px solid black;
        height: 194.67px;
       
           li{
            list-style: none;
            color: gray;
           }
           h2{
            color: white;
           }
          
    }
    .contenitore-lista-tre{
        border: 1px solid black;
        height: 194.67px;
        
           li{
            list-style: none;
            color:gray;
            
           }
           h2{
            color: white;
           }
    }
    .logo-big{
          margin-left: auto;
        img{
            max-width: 100%;
           
        }
    }

    
   
}

</style>
