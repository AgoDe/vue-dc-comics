<template>
    <div class="footer-special">

        <div class="flex-box">

            <div class="item-box">
                <img src="@/assets/img/buy-comics-digital-comics.png" alt="digital comics">
                <div>DIGITAL COMICS</div>
            </div>

            <div class="item-box">
                <img src="@/assets/img/buy-comics-merchandise.png" alt="digital comics">
                <div>DIGITAL COMICS</div>
            </div>

            <div class="item-box">
                <img src="@/assets/img/buy-comics-subscriptions.png" alt="digital comics">
                <div>DIGITAL COMICS</div>
            </div>

            <div class="item-box">
                <img src="@/assets/img/buy-comics-shop-locator.png" alt="digital comics">
                <div>DIGITAL COMICS</div>
            </div>

            <div class="item-box">
                <img src="@/assets/img/buy-dc-power-visa.svg" alt="digital comics">
                <div>DIGITAL COMICS</div>
            </div>

        </div>


        

      

    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    @import '@/styles/variables.scss';

    .footer-special {
        padding: 30px 0;
        background-color: $tipically-blue;

        .flex-box {
            width: $max-width;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            
            .item-box {
                display: flex;
                align-items: center;
                color: white;
                
    
                img {
                    height: 30px;
                }
                div {
                    margin-left: 8px;
                    font-size: 13px;
                }
            }
        }
    }

</style>