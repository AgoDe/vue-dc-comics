<template>
    <main>
        <div class="jumbotron"></div>
        
        <div class="card-container">

            <div class="article-title"> CURRENT SERIES</div>   

            <div class="flex-box">
                <!-- stampa dell'array dei fumetti -->
                <div v-for="(item, index) in comics" :key="index"
                class="card-box"
                >  
                    <img :src="item.thumb" alt="">   
                    <h4> {{ item.series}} </h4>
                </div>
            </div>

            <div class="load-button">LOAD MORE</div>
            
            

        </div>
    </main>
</template>

<script>
export default {
    props: {
        comics: Array,
    }
    
}
</script>

<style lang="scss" scoped>
    @import '@/styles/variables.scss';
    main {
        background: black;
        color: white;

        .jumbotron {
            height: 400px;
            background-image: url(../assets/img/jumbotron.jpg);
            background-size: cover;
        }

      

        .card-container {
            width: $max-width;
            margin: 0 auto;
            padding: 30px 0;
            position: relative;

            .article-title {
                position: absolute;
                top:-25px;
                background: $tipically-blue;
                height: 50px;
                line-height: 50px;
                width: 170px;
                text-align: center;
                font-weight: bold;
            }
            .flex-box {
                display: flex;
                justify-content: space-around;
                flex-wrap: wrap;

                .card-box {
                    width: 130px;
                    text-align: center;
                    padding: 15px 0;

                    img {
                        width: 130px;
                        height: 130px;
                        object-fit: cover;
                        object-position: top
                    };
                    h4 {
                        padding: 10px 0;
                    }
   
                }
            }

            .load-button {
                background: $tipically-blue;
                height: 40px;
                line-height: 40px;
                width: 120px;
                text-align: center;
                margin: 0 auto;


            }



        }
    }
</style>